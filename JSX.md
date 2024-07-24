# Create the README.md file with the specified content
readme_content = """
# Aturan JSX

## 1. Selalu mengembalikan satu elemen

### Code
```jsx
function MyApp() {
  return (
    <>
      <h1
        style={{
          background: "linear-gradient(to right, #4facfe, #00f2fe)",
          WebkitBackgroundClip: "text",
          color: "transparent",
        }}
      >
        Belajar React manual bareng pak Mirza 🌍
      </h1>
      <h1
        style={{
          background: "linear-gradient(to right, #4facfe, #00f2fe)",
          WebkitBackgroundClip: "text",
          color: "transparent",
        }}
      >
        Belajar React manual bareng pak Mirza 🌍
      </h1>
      <button onClick={(e) => alert('ok')}>Semangat!</button>
    </>
  );
}
