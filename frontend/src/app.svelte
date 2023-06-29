<script>
    let count = 0;
  
    function increment() {
      count += 1;
    }
  </script>
  
  <main>
    <h1>InteractWeb</h1>
    <p>Count: {count}</p>
    <button on:click={increment}>Increment</button>
  </main>
  
  <style>
    main {
      text-align: center;
      padding: 2rem;
      font-family: Arial, sans-serif;
    }
  </style>
  