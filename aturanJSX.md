# My React Component

This is a simple React component that displays a heading with a linear gradient text effect.

## Code

```jsx
function MyApp() {
  return (
    <h1
      style={{
        background: 'linear-gradient(to right, #4facfe, #00f2fe)',
        WebkitBackgroundClip: 'text',
        color: 'transparent',
      }}
    >
      Belajar React manual bareng pak Mirza 🌍
    </h1>
  );
}
