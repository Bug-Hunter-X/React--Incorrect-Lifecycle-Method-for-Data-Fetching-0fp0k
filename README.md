# React Lifecycle Method Bug

This repository demonstrates a common bug in React functional components involving the incorrect use of lifecycle methods for data fetching. The original code uses the deprecated `componentWillMount` method. The corrected code uses the `useEffect` hook with an empty dependency array, providing a more reliable solution.