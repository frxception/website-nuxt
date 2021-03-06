<template>
  <div class="flex flex-wrap">
    <div class="pt-4 pb-4 w-full lg:pr-8 lg:w-1/3">
      <netflix-logo class="h-8 w-auto"/>

      <p>
        We were integrated with the Studio Finance UI team at Netflix, working primarily on Gravity, which is a
        financial app that allows users to upload and edit large amounts of data about shows and movies. It was a
        mostly unmaintained app when we started, and we were tasked with whipping it into shape and increasing the
        code coverage from tests.
      </p>
    </div>

    <div class="pt-4 pb-4 w-full lg:pl-4 lg:pr-4 lg:w-1/3">
      <social-code-logo class="h-8 w-auto"/>

      <p>
        SocialCode has a unique "micro apps" setup, which we helped streamline, by moving common dependencies to a
        common addon, and ensuring all apps adhered to the same standards by enforcing the latest eslint-plugin-ember
        rules. We also migrated all the code to use the new modules syntax, and new testing syntax, and updated apps
        to the latest Ember version to make sure we were on the latest and greatest of everything.
      </p>
    </div>

    <div class="pt-4 pb-4 w-full lg:pl-8 lg:w-1/3">
      <a href="https://marianatek.com/">
        <mariana-tek-logo class="h-8 w-auto"/>
      </a>

      <p>
        We worked hand in hand with the Mariana Tek dev team to develop several required features for a major
        client release. This included an initial scan of the codebase, the addition of several ESLint rules from
        eslint-plugin-ember, and updates of various dependencies. We enforced best practices at every turn, and ensured the
        code looked very consistent, no matter who wrote it.
      </p>
    </div>

    <div class="pt-4 pb-4 w-full lg:pr-8 lg:w-1/3">
      <a href="https://www.scoutforpets.com/">
        <scout-logo class="h-8 w-auto"/>
      </a>
      <p>
        We did several months of work with Scout,
        starting with updating to the latest versions of
        Ember and Ember CLI, adding Ember Suave, and adhering
        to the new set of ESLint rules.

        We worked extensively on the appointment scheduling
        aspects of the app, creating full screen overlays,
        using Ember Flatpickr, Ember Paper and Ember Power Select,
        to allow a customer or staff member to create or edit an
        appointment.
      </p>
    </div>

    <div class="pt-4 pb-4 w-full lg:pl-4 lg:pr-4 lg:w-1/3">
      <a href="https://www.greenlight.guru/">
        <greenlight-guru-logo class="h-8 w-auto"/>
      </a>
      <p>
        We first updated the greenlight.guru app to Ember 1.12, fixing deprecations as we went.
        After 1.12 was complete, we undertook the task of migrating a grunt based build to ember-cli.
        We finally updated the app to Ember 1.13 and fixed all the deprecations.
      </p>
    </div>

    <div class="pt-4 pb-4 w-full lg:pl-8 lg:w-1/3">
      <a href="https://www.mentrs.com/">
        <mentrs-logo class="h-8 w-auto"/>
      </a>

      <p>
        We worked on the Mentrs MVP from the ground up,
        starting with running 'ember new', and adding all the addons,
        ESLint plugins, template lintings, and doing all the initial
        work required to create an Ember app, rooted in the latest Ember standards.

        Features we implemented included everything from login and sign up,
        to class creation, and Stripe integration for paying to enroll in classes.
      </p>
    </div>
  </div>
</template>

<script>
  import GreenlightGuruLogo from '~/assets/svgs/clients/greenlight-guru.svg?inline';
  import MarianaTekLogo from '~/assets/svgs/clients/mariana-tek-full.svg?inline';
  import MentrsLogo from '~/assets/svgs/clients/mentrs.svg?inline';
  import NetflixLogo from '~/assets/svgs/clients/netflix.svg?inline';
  import ScoutLogo from '~/assets/svgs/clients/scout.svg?inline';
  import SocialCodeLogo from '~/assets/svgs/clients/socialcode.svg?inline';

  export default {
    components: {
      GreenlightGuruLogo,
      MarianaTekLogo,
      MentrsLogo,
      NetflixLogo,
      ScoutLogo,
      SocialCodeLogo
    }
  };
</script>
