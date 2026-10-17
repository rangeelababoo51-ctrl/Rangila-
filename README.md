# Rangila-<input id="q" placeholder="Google me search karo">
<button onclick="s()">Search</button>
<script>
function s(){
  var q = document.getElementById('q').value;
  window.location.href = "https://www.google.com/search?q=" + encodeURIComponent(q);
}
</script>
