# React 18 SSR app (renderToPipeableStream)

A server-rendered shell designed to compose and orchestrate multiple self-contained interactive components within a shared layout while minimizing performance overhead.

The server streams HTML, while the client progressively enables heavier features based on visibility, user input, and idle time.

Image content is progressively enhanced in quality to prioritize early visibility without sacrificing final fidelity. Video media uses WebM with MP4 and still-image fallbacks.

The dynamic app is mounted separately inside a shadow root to prevent style bleed and layout shifts.