<template>
    <div>
      <span id="typed"></span>
    </div>
</template>
  
<script>
  import Typed from 'typed.js';
  
  export default {
    mounted() {
      var options = {
        typeSpeed: 40,
        stringsElement: "#poem",
        loop: false,
        startDelay: 2000,
        cursorChar: "●",
        onComplete: (self) => {
          var rootElement = this.$root.$el;
          if (rootElement) {
            rootElement.style.backgroundColor = "#173564";
            rootElement.style.color = "#ECE3D5";
            var button = document.querySelector(".button");
            if (button) {
                button.style.backgroundColor = "#ECE3D5";
                button.addEventListener("mouseenter", () => {
                    button.style.backgroundColor = "#FEDE5D";
              });
                button.addEventListener("mouseleave", () => {
                    button.style.backgroundColor = "#ECE3D5";
              });
            }
          }
        },
      };
  
      var typed = new Typed("#typed", options);
    }
  }
</script>
  