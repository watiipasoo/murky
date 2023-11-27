<script>
    import "../app.css";
    import Navigation from "../components/Navigation/navigation.svelte";
  </script>
  
  <div>
    <div>
      <img src="/ell.svg" alt="" class="absolute"/>
      <Navigation/>
    </div>
    
      <slot />
  </div>
