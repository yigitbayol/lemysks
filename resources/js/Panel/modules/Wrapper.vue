<template>
  <!--begin::Content-->
  <div class="content d-flex flex-column flex-column-fluid" id="kt_content">
    <!--begin::Subheader-->
    <div class="subheader py-2 py-lg-6 subheader-solid" id="kt_subheader">
      <div
        class="container-fluid d-flex align-items-center justify-content-between flex-wrap flex-sm-nowrap"
      ></div>
    </div>
    <!--end::Subheader-->
    <!--begin::Entry-->
    <div class="d-flex flex-column-fluid">
      <!--begin::Container-->
      <div class="container">
        <slot></slot>
      </div>
      <!--end::Container-->
    </div>

    <!--end::Entry-->
  </div>
  <!--end::Content-->
</template>

<script>
export default {};
</script>
