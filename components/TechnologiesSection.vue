<template>
  <div class="section flex flex-wrap justify-center lg:mb-12">
    <div class="section-content">
      <div class="flex flex-wrap">
        <div class="w-full lg:w-1/5 text-center lg:text-left">
          <h3 class="heading text-5xl">
            Technologies we use
          </h3>
        </div>

        <div class="flex flex-wrap w-full lg:pl-32 lg:w-4/5 text-grey">
          <div class="w-1/2 sm:w-1/3 flex justify-center items-center">
            <Ember :class="'w-full h-full p-4 max-w-xxs'"/>
          </div>
          <div class="w-1/2 sm:w-1/3 flex justify-center items-center">
            <EmberCLI :class="'w-full h-full p-4 max-w-xxs'"/>
          </div>
          <div class="w-1/2 sm:w-1/3 flex justify-center items-center">
            <EmberData :class="'w-full h-full p-4 max-w-xxs'"/>
          </div>
          <div class="w-1/2 sm:w-1/3 flex justify-center items-center">
            <Node :class="'w-full h-full p-4 max-w-xxs'"/>
          </div>
          <div class="w-1/2 sm:w-1/3 flex justify-center items-center">
            <Sass :class="'w-full h-full p-4 max-w-xxs'"/>
          </div>
          <div class="w-1/2 sm:w-1/3 flex justify-center items-center">
            <Travis :class="'w-full h-full p-4 max-w-xxs'"/>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
  import Ember from '~/assets/svgs/technologies/ember.svg?inline';
  import EmberCLI from '~/assets/svgs/technologies/embercli.svg?inline';
  import EmberData from '~/assets/svgs/technologies/emberdata.svg?inline';
  import Node from '~/assets/svgs/technologies/node.svg?inline';
  import Sass from '~/assets/svgs/technologies/sass.svg?inline';
  import Travis from '~/assets/svgs/technologies/travis.svg?inline';

  export default {
    components: {
      Ember,
      EmberCLI,
      EmberData,
      Node,
      Sass,
      Travis
    }
  };
</script>
