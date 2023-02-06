![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=darko5r&theme=dark&show_icons=true)

![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=darko5r&layout=compact&theme=dark)

<details>
  <summary>
    Content
  </summary>
  <div class="content">
    Your collapsed content goes here...
  </div>
</details>

<style>
  .collapsible {
    background-color: #777;
    color: white;
    cursor: pointer;
    padding: 18px;
    width: 100%;
    border: none;
    text-align: left;
    outline: none;
    font-size: 15px;
  }

  .active, .collapsible:hover {
    background-color: #555;
  }

  .content {
    padding: 0 18px;
    max-height: 0;
    overflow: hidden;
    transition: max-height 0.2s ease-out;
    background-color: #f1f1f1;
  }
</style>

<button class="collapsible">Click to expand +</button>
<div class="content">
  Your collapsed content goes here...
</div>

<script>
  var coll = document.getElementsByClassName("collapsible");
  var i;

  for (i = 0; i < coll.length; i++) {
    coll[i].addEventListener("click", function() {
      this.classList.toggle("active");
      var content = this.nextElementSibling;
      if (content.style.maxHeight) {
        content.style.maxHeight = null;
        this.innerHTML = "Click to expand +";
      } else {
        content.style.maxHeight = content.scrollHeight + "px";
        this.innerHTML = "Click to collapse -";
      } 
    });
  }
</script>
