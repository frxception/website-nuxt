<template>
  <div class="section flex flex-wrap justify-center">
    <div class="section-content">
      <div class="flex flex-wrap items-center pt-6 pb-6">
        <div class="w-full text-center lg:pr-12 lg:text-left lg:w-1/2">
          <Design :class="'max-w-md'"/>
        </div>

        <div class="w-full flex lg:pl-12 lg:justify-end lg:w-1/2">
          <div class="lg:max-w-md">
            <h3 class="heading">
              Design
            </h3>
            <h3 class="sub-heading">
              Measure twice, cut once
            </h3>

            <p>
              We take the time necessary to develop a sound architecture and to ensure we
              have a solid understanding of your wants and needs. We'll work together as
              partners, to develop a game plan, and collaborate every step of the way.
            </p>
          </div>
        </div>
      </div>

      <div class="flex flex-wrap items-center flex-col-reverse pt-6 pb-6 lg:flex-row">
        <div class="w-full flex lg:pr-12 lg:w-1/2">
          <div class="lg:max-w-md">
            <h3 class="heading">
              Build
            </h3>
            <h3 class="sub-heading">
              Convention over configuration
            </h3>

            <p>
              We use the latest versions of Ember.js and Ember-CLI in all of our projects,
              and leverage the amazing <a href="/ember-consulting/">Ember community</a>, and its huge breadth of
              <a href="/open-source/">addons</a> to help us iterate faster, and focus on making quality apps,
              instead of reinventing the wheel.
            </p>
          </div>
        </div>

        <div class="w-full text-center lg:pl-12 lg:text-right lg:w-1/2">
          <Build :class="'max-w-md'"/>
        </div>
      </div>

      <div class="flex flex-wrap items-center pt-6 pb-6">
        <div class="w-full text-center lg:pr-12 lg:text-left lg:w-1/2">
          <Ship :class="'max-w-md'"/>
        </div>

        <div class="w-full flex lg:pl-12 lg:justify-end lg:w-1/2">
          <div class="lg:max-w-md">
            <h3 class="heading">
              Ship
            </h3>
            <h3 class="sub-heading">
              All Aboard
            </h3>

            <p>
              We'll keep you in the loop with regular demos, frequent calls, chats, dinners,
              drinks—whatever floats your boat. Your input and collaboration are crucial to making
              sure you are 100% happy with the product.
            </p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
  import Build from '~/assets/svgs/illustrations/build.svg?inline';
  import Design from '~/assets/svgs/illustrations/design.svg?inline';
  import Ship from '~/assets/svgs/illustrations/ship.svg?inline';

  export default {
    components: {
      Build,
      Design,
      Ship
    }
  };
</script>
