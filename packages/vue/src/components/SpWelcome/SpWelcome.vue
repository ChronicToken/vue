<template>
  <div class="sp-component sp-welcome">
    <div class="sp-box sp-shadow sp-welcome__main">
      <div class="sp-welcome__header">
        <h2>Welcome to Chronic Chain wallet dashboard</h2>
      </div>
      <p>
        Chronic Chain is built using the CosmosSDK and starport, utilizing these tools has allowed us to develop our
        blockchain.<br />
        With this dashboard users are able to interact with the Chronic Blockchain<br />
      </p>
      <div class="sp-welcome__btns">
        <SpButton href="https://chronictoken.io/" target="_blank" type="primary">Documentation</SpButton>
        <SpButton
          href="https://github.com/ChronicNetwork"
          target="_blank"
          type="secondary"
          class="sp-welcome__btns__github"
          >Github</SpButton
        >
      </div>
    </div>
  </div>
</template>
<script lang="ts">
import { defineComponent } from 'vue'
import SpButton from '../SpButton'

export default defineComponent({
  name: 'SpWelcome',
  components: {
    SpButton,
  },
})
</script>
