<template>
  <form>
    <!-- Name -->
    <div class="field">
      <label class="label is-medium">Name</label>
        <input class="input is-medium" type="text" placeholder="John Smith" />
    </div>
    <!-- Email -->
    <div class="field">
      <label class="label is-medium">Email</label>
        <input
          class="input is-medium"
          type="email"
          placeholder="you@email.com"
        />
    </div>
    <!-- Subject -->
    <div class="field">
      <label class="label is-medium">Subject</label>
        <input
          class="input is-medium"
          type="text"
          placeholder="Brief Summary"
        />
    </div>
    <!-- Message -->
    <div class="field">
      <label class="label is-medium">Message</label>
        <textarea
          class="textarea"
          placeholder="Detailed description of your comment, request, etc"
          rows="8"
        ></textarea>
    </div>
      <button class="button is-primary">
        Contact Us
      </button>
  </form>
</template>
