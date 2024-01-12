<template>
  <div class="container-fluid py-4">
    <div class="row">
      <div class="col-12">
        <div class="card my-4">
          <div class="card-header p-0 position-relative mt-n4 mx-3 z-index-2">
            <div
              class="bg-gradient-success shadow-success border-radius-lg pt-4 pb-3"
            >
              <h6 class="text-white text-capitalize ps-3">Patients</h6>
            </div>
          </div>
          <div class="card-body px-0 pb-2">
            <material-input
                          id="email"
                          type="email"
                          label="Email"
                          name="email"
                          size="lg"
                        />
                     
          </div>
        </div>
      </div>
  

    </div>

  </div>
</template>

<script>
import MaterialInput from "@/components/MaterialInput.vue";
import MaterialCheckbox from "@/components/MaterialCheckbox.vue";
import MaterialButton from "@/components/MaterialButton.vue";

export default {
  name: "newpatient",
  MaterialInput,
  MaterialCheckbox,
  MaterialButton,

  beforeMount() {
 
  },
  methods: {
    //...mapMutations(["toggleEveryDisplay", "toggleHideConfig"]),
  },


};
</script>
