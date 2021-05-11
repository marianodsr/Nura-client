<script lang="typescript">
  import ExoLogo from "../../components/icons/ExoLogo.svelte";

  import LoginForm from "../../components/LoginForm.svelte";
 
</script>

<main>
  <div class="container">
    <ExoLogo ref="login-logo" />
    <LoginForm />
  </div>
</main>

<style>
  .container {
    background: var(--primary-dark);
    width: 100vw;
    height: 100vh;
    color: var(--primary-light);
    display: flex;
    flex-direction: column;
    align-items: center;
    padding-top: 25%;
  }
  :global([ref="login-logo"]) {
    width: 12rem;
    height: 12rem;
    margin-bottom: 2rem;
  }
 
</style>
