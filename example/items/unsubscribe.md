## Aw.
<form id="unsubscribe-form">
        <input type="text" name="email" id="unsubscribe-email" placeholder="your-email@example.com">
        <button type="submit" value="unsubscribe" onclick="document.getElementById('unsubscribe-message').innerHTML = 'unsubscribed!'"> unsubscribe </button>
        <a id="unsubscribe-message"></a>
</form>
<script>
let unsubscribeForm = document.getElementById("unsubscribe-form");
unsubscribeForm.addEventListener("submit", (e) => {
  e.preventDefault();
  let email = document.getElementById("unsubscribe-email").value;
  var ImageObject = new Image();
  ImageObject.src = "https://ml.dreadmaw.industries/unsubscribe?email=" + email;
});
</script>
