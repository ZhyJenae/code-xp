<template>
<div>
  <PageHeader title="Code Xp Conference" date="August 19th, 2021"/>
  <div class="wrapper">
    <Agenda/>
    <SpeakerSection name="Vantol Bennett" jobDescription="Developer | Content Creator" :description="description"/>
    <Signup/>
  </div>
  <Footer/>
</div>
</template>

<script>
// FIXME: Fix the icons import and all icons in the app
// TODO: Create a new page layout for blog section
import 'vue-awesome/icons'
export default {
  data() {
    return {
      description: 'Code, Learn and Inspire! Coding is more than just thing we do... is something feel!'
    }
  }
}
</script>

