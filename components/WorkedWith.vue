<template>
  <div class="section flex flex-wrap justify-center">
    <div class="section-content">
      <div class="text-center w-full">
        <h3 class="heading pb-8">
          We've had the pleasure of working with
        </h3>
      </div>

      <div class="flex flex-wrap items-center w-full pb-8">
        <div class="client-logo">
          <ScoutLogo :class="'h-full w-full max-w-xs'"/>
        </div>
        <div class="client-logo">
          <GreenlightGuruLogo :class="'h-full w-full max-w-xs'"/>
        </div>
        <div class="client-logo">
          <NetflixLogo :class="'h-full w-full max-w-xs'"/>
        </div>
        <div class="client-logo">
          <MarianaTekLogo :class="'h-full w-full max-w-xs'"/>
        </div>
        <div class="client-logo">
          <SocialCodeLogo :class="'h-full w-full max-w-xs'"/>
        </div>
      </div>

      <div class="flex justify-center w-full">
        <nuxt-link to="/work" class="btn-navy mb-12">
          View case studies
        </nuxt-link>
      </div>
    </div>
  </div>
</template>

<script>
  import GreenlightGuruLogo from '~/assets/svgs/clients/greenlight-guru.svg?inline';
  import MarianaTekLogo from '~/assets/svgs/clients/mariana-tek-full.svg?inline';
  import NetflixLogo from '~/assets/svgs/clients/netflix.svg?inline';
  import ScoutLogo from '~/assets/svgs/clients/scout.svg?inline';
  import SocialCodeLogo from '~/assets/svgs/clients/socialcode.svg?inline';

  export default {
    components: {
      GreenlightGuruLogo,
      MarianaTekLogo,
      NetflixLogo,
      ScoutLogo,
      SocialCodeLogo
    }
  };
</script>
