<script>
  let count = $state(0)
</script>

<main>
  <h1>Time Tracker — Support</h1>
  <p>Track time with Pomodoro and quick entry. View calendar and statistics.</p>

  <p>
    <button onclick={() => (count += 1)}>Clicked {count} {count === 1 ? 'time' : 'times'}</button>
  </p>

  <p>
    <a href="mailto:support@example.com">Contact: support@example.com</a>
  </p>
</main>

<style>
  main {
    text-align: left;
  }
  h1 {
    font-size: 1.5rem;
    margin-top: 0;
  }
  button {
    padding: 0.5rem 1rem;
    font-size: 1rem;
    cursor: pointer;
  }
  a {
    color: #2563eb;
  }
</style>
