<template>
  <div>
    <div
      v-if="success !== null"
      class="alert alert-custom alert-notice alert-light-success fade show mb-5"
      role="alert"
    >
      <div class="alert-icon"><i class="flaticon-warning"></i></div>
      <div class="alert-text">
        {{ success }}
      </div>
      <div class="alert-close">
        <button
          type="button"
          class="close"
          data-dismiss="alert"
          aria-label="Close"
        >
          <span aria-hidden="true"><i class="ki ki-close"></i></span>
        </button>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      success: null,
    };
  },
};
</script>
