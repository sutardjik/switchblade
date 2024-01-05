<template>
  <main>
    <div class="content">
      <div class="content-container">
        <h1>Switchblade</h1>
        <h2 style="margin-bottom: 5px">
          <span class="context">A GENERATED POEM</span>
        </h2>
        <button class="button">
          <a
            href="https://sutardjik.github.io/"
            target="_self"
            style="
              color: #173564 !important;
              cursor: url('/img/pointer.png'), auto;
            "
            >BY &#x4b;&#x41;&#x52;&#x45;&#x4e;
            &#x53;&#x55;&#x54;&#x41;&#x52;&#x44;&#x4a;&#x49;</a>
        </button><br /><br /><br />
        <span id="typed"></span>
        <TypingComponent />
        <div id="poem">
          <h2>
            Legend says you performed self-hypnosis<br />
            Conjuring me up as your dream girl<br />
            Painted me as your favorite enigma<br />
            Was I your Renaissance girl<br />
            Or your pixel princess?<br /><br />

            Oh personified Narcissus<br />
            I am not a reflection<br />
            On the other side of the mirror<br />
            You fell to the spell of King Midas’ touch<br />
            But all that glitters is not gold<br />
            I carry your Achilles heel<br />
            Into the labyrinth of my mind<br />
            But my bloodstain taints yours<br /><br />

            On the night of Crucifix Eve<br />
            We waltzed in 3/4 time to “Danse Macabre”<br />
            Accompanied by the Last Supper<br />
            There was writing on the wall<br />
            When the clock struck midnight<br />
            You pulled the plug on Martyrs’ Hill<br />
            A calling ticket to the underworld<br /><br />

            I’m a free thinker<br />
            Can you handle the heat?<br />
            Prophecy revealed you’ll see me<br />
            Everywhere in everyone<br />
            I’m running until the new dawn<br />
            Disappearing into the sun<br />
            Bet you can’t catch me now<br /><br />

            The final puzzle piece doesn’t exist<br />
            Save yourself before drowning<br />
            In your wishful thinking<br />
            Pandora’s box was never yours to open<br />
            The enigma never unraveled itself<br />
            You never knew me after all
          </h2>
        </div>
      </div>
    </div>
  </main>
</template>

<script>
import TypingComponent from './components/TypingComponent.vue';
export default {
  components: {
    TypingComponent,
  },
}
</script>
