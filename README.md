# Infinite Rendering Bug in React

This repository demonstrates a common React bug: infinite rendering caused by an improperly used `useEffect` hook. The `useEffect` hook, without a dependency array, re-renders the component endlessly, leading to performance issues and potential crashes.  The solution demonstrates how to correctly use the dependency array to prevent this issue.