<script>
  if (!sessionStorage.getItem("reloaded")) {
    sessionStorage.setItem("reloaded", "true");
    window.location.reload();
  } else {
    sessionStorage.removeItem("reloaded");
  }
</script>

# Blog