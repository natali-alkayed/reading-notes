## useEffect() Hook
1. What is the main intended use case for the useEffect hook?
The useEffect hook is a fundamental part of React's functional component paradigm. Its main intended use case is to handle side effects in your components. Side effects are operations that are not directly related to rendering UI, such as data fetching, subscriptions, or manually changing the DOM.

In React, components are re-rendered whenever their state or props change. However, there are times when you need to perform actions that are not directly tied to rendering, such as fetching data from a server or setting up event listeners. This is where useEffect comes into play.
The basic structure of the useEffect hook is as follows:

useEffect(() => {
  // Effect logic goes here

  // Return a cleanup function (optional)
  return () => {
    // Clean up any resources or subscriptions if needed
  };
}, [dependencyArray]);

Here's how the useEffect logic interacts with the component:

Mounting Phase: When the component is first mounted (rendered), the effect logic within the useEffect block is executed.

Updating Phase: If the component's dependencies (specified in the dependencyArray) change on subsequent renders, the effect logic is re-executed.

Unmounting Phase: If the component is being unmounted (removed from the UI), the optional cleanup function returned from the useEffect is executed.

The dependencyArray is crucial for controlling when the effect should run. It contains values (typically state variables or props) that the effect depends on. If any of the values in the dependency array change between renders, the effect is re-run. If the dependency array is empty, the effect will only run once after the initial render.

The return value from the effect's logic function is used for cleanup. This is especially important when dealing with operations like subscriptions or event listeners that need to be removed when the component is unmounted or when the effect is re-run due to dependency changes. The cleanup function returned from the useEffect is executed before the next execution of the effect or when the component is unmounted.

Here's an example illustrating the use of useEffect for data fetching:
import React, { useState, useEffect } from 'react';

function DataFetchingComponent() {
  const [data, setData] = useState(null);

  useEffect(() => {
    // Fetch data from an API
    fetch('https://api.example.com/data')
      .then(response => response.json())
      .then(data => setData(data));

    // Cleanup function to cancel any ongoing requests when the component is unmounted or re-rendered
    return () => {
      // Cancel ongoing requests or perform any cleanup
    };
  }, []); // Empty dependency array means the effect runs only once after the initial render

  return (
    <div>
      {/* Render the fetched data */}
      {data && <p>{data.message}</p>}
    </div>
  );
}
In this example, the useEffect hook is used to fetch data from an API when the component is mounted. The cleanup function ensures that any ongoing requests are canceled if the component is unmounted or if the effect is re-run.