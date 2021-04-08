<template>
  <section class="section mt-6">
    <form class="">
      <h3 class="content is-large has-text-centered">
        Get in <b class="has-text-primary has-text-weight-bold">Contact</b>.
        <br />Fill up the form below. All fields are required.
      </h3>
      <div class="columns is-multiline">
        <div class="column is-6">
          <div class="field">
            <div class="control is-expanded">
              <input type="text" class="input" placeholder="Your Name" />
            </div>
          </div>
        </div>
        <div class="column is-6">
          <div class="field">
            <div class="control is-expanded">
              <input type="email" class="input" placeholder="Your Email" />
            </div>
          </div>
        </div>
        <div class="column is-full">
          <textarea
            name="mss"
            class="textarea"
            placeholder="Your Feedback"
          ></textarea>
        </div>
        <div class="column is-full has-text-centered">
          <input type="submit" name="submit" value="SUBMIT" class="button" />
        </div>
      </div>
    </form>
  </section>
</template>
<script type="text/javascript">
export default {
  name: "forms"
};
</script>

<style media="screen"></style>
