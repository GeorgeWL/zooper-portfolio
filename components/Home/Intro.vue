<template>
  <div class="space-y-6">
    <NuxtImg src="/avatar.png" alt="GeorgeWL"
      class="ring-2 border ring-gray-200 border-gray-300 dark:ring-white/10 dark:border-gray-800 hover:ring-4 transition-all duration-300 bg-gray-200 dark:bg-gray-900 rounded-full h-12 w-12 sm:h-16 sm:w-16"
      sizes="48px sm:64px" placeholder format="webp" />
    <AppHeadersHeader1>
      Hello!
    </AppHeadersHeader1>
    <Text>
      I'm George - currently working as a Software Developer for <AppAnchor href="//autodesk.co.uk">Autodesk</AppAnchor>
      , in the <AppAnchor href='//construction.autodesk.com/'>Construction cloud</AppAnchor>
      product team.

      I'm based in <AppAnchor href="https://maps.app.goo.gl/pZBKSP3EMGRqC7cp6">North West Manchester</AppAnchor>, a
      region of Greater Manchester in
      the United Kingdom.
    </Text>
    <AppHeadersHeader2>
      My Interests
    </AppHeadersHeader2>
    <Text>
      I'm interested in Web Apps, UX, and Programming. I'm a frontend developer with a passion for accesibility and user
      experience.
      I specialize in building web applications and sites using Javascript, React, Vue & Node.
      <br />
      <br />
      I also do quite a few hobbies in my spare time;
    </Text>
    <AppUnorderListSpaced>
      <AppUnorderListSpaced>
        <li>🎮 pc gaming</li>
        <li>🎹 piano</li>
        <li>🚲 biking and inline skating</li>
        <li>⚔ tabletop RPGs</li>
        <li>🧗‍♂️ bouldering</li>
      </AppUnorderListSpaced>
      <li>I'm currently learning the UI frameworks of <AppAnchor href="https://svelte.dev">Svelte</AppAnchor> and
        <AppAnchor href="https://vuejs.org">VueJS</AppAnchor> in my spare time
      </li>
    </AppUnorderListSpaced>
    <br />
    <Text>🚫 I am <strong>NOT</strong> Looking for roles, so <strong>don't</strong> send me job adverts.🚫</Text>
  </div>
</template>

<script setup>
useSeoMeta({
  title: "GeorgeWL",
  description:
    "I'm Fayaz, your friendly neighborhood software, product engineer and designer from Bengaluru, India. I specialize in building web applications and sites using Javascript, React, Vue & Node.",
});
</script>
