<script>
  let count = $state(0)
</script>

<main style="--logo-url: url('{import.meta.env.BASE_URL}PomoTimeTrackerLogo.PNG')">
  <h1>PomoTimeTracker — Support page</h1>
  <p>Track time with Pomodoro and quick entry. View calendar and statistics of activities with ease.</p>

  <p>
    <a href="mailto:pomotimetracker@outlook.com">Contact: pomotimetracker@outlook.com</a>
  </p>

  <p>
    <a href="{import.meta.env.BASE_URL}TimeTracker_demo.pdf">Download demonstration file (PDF)</a>
  </p>

  <p>
    <a href="{import.meta.env.BASE_URL}privacy.html">Privacy Policy</a>
  </p>
</main>

<style>
  main {
    text-align: left;
    position: relative;
    min-height: 60vh;
  }
  main::before {
    content: '';
    position: absolute;
    inset: 0;
    background: var(--logo-url) center / contain no-repeat;
    opacity: 0.15;
    z-index: -1;
    pointer-events: none;
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
