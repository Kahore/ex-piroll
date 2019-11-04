<template>
  <form>
    <div class="form-inline d-flex justify-content-between">
      <div class="form-group mb-2 w-50">
        <input
          type="text"
          class="form-control w-75"
          required
          id="contactName"
          placeholder="Your Name">
      </div>
      <div class="form-group mb-2 w-50">
        <input
          type="email"
          required
          class="form-control w-100"
          id="contactEmail"
          placeholder="Your Email">
      </div>
    </div>
    <div class="form-group">
      <input
        type="text"
        required
        class="form-control"
        id="contactTitle"
        placeholder="Your Title">
    </div>
    <div class="form-group">
      <textarea
        rows="4"
        required
        id="contactBody"
        placeholder="Your Comment"
        class="form-control"></textarea>
    </div>
    <div class="form-group">
      <button class="btn btn-primary">SEND MESSAGE</button>
    </div>
  </form>
</template>
