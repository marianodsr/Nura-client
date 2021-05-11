<script lang="ts">
  import { Router } from "@roxi/routify";
  import { routes } from "../.routify/routes";
</script>

<style  global>
  @import "../assets/global.css";
  :global(:root) {
    --primary-dark:#222831;
    --primary-blue: #30475e;
    --primary-light: #ececec;
    --contrasting-orange: #f2a365;
    box-sizing: border-box;
    font-family: 'Roboto';
    margin: 0;
    padding: 0;
  }
</style>

<Router {routes} />