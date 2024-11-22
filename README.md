Day 7: 🛠️ Using `useEffect` for Side Effects

`useEffect` is used for side effects in functional components. Here’s an example that logs data when the component mounts:  jsx  
useEffect(() => { console.log('Component mounted'); }, []);  

What side effects have you used in your app? #ReactJS #React30Challenge"



Day 8: 🌐 Fetching Data with `useEffect`

Fetching data is essential. Here’s an example using `useEffect` and `fetch`:  
jsx  
useEffect(() => { fetchData(); }, []);  

What API are you consuming today? #ReactJS #React30Challenge"





# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh
