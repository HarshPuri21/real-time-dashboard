High-Performance Real-Time Data Dashboard

A high-performance dashboard built with React, TypeScript, and D3.js to visualize thousands of real-time data points from a mock WebSocket stream. This project demonstrates advanced frontend techniques for handling large, dynamic datasets while maintaining a fluid user experience.

Live Demo: [Link to your deployed site] <!--- Add a link here after deploying to a service like Vercel or Netlify -->

<!--- Add a screenshot of your project! -->
Key Features & Technical Highlights

    Real-Time Charting: Utilizes D3.js to render a smooth, live-updating line chart from a continuous data stream.

    List Virtualization ('Windowing'): The data log on the right can handle thousands of entries without performance degradation. It only renders the DOM nodes that are currently visible to the user.

    Component Memoization: React.memo is used to prevent the complex D3 chart from re-rendering unnecessarily, optimizing application performance.

    Responsive Design: The chart and layout are fully responsive and adapt to different screen sizes using a custom ResizeObserver hook.

    Custom Hooks: Logic for the WebSocket connection and responsive resizing is cleanly abstracted into custom React hooks.

    Modern Tech Stack: Built with React, TypeScript, D3.js, and styled with Tailwind CSS.
