<template>
  <div class="flex bg-gray-800 py-20 px-10 overflow-y-scroll">
    <div
      class="m-auto grid grid-cols-1 md:grid-cols-3 lg:grid-cols-4 p-2 gap-2"
    >
      <!-- CARD START -->
      <card>
        <template v-slot:company-logo>
          <Logo class="w-full m-auto" />
        </template>
        <template v-slot:company-name> TheLEAD.io | LEAD </template>
        <template v-slot:job-details
          >Lorem ipsum dolor sit amet consectetur adipisicing elit. Placeat unde
          quas beatae impedit aspernatur illum voluptate, praesentium
          dignissimos in minima aperiam debitis excepturi. Mollitia soluta,
          delectus obcaecati aut eius placeat!</template
        >
        <template v-slot:job-title>Instructor</template>
      </card>
      <card>
        <template v-slot:company-logo>
          <img
            src="https://a.staticaa.com/images/logos/airasiacom_monogram.svg"
            alt=""
          />
        </template>
        <template v-slot:company-name> AirAsia </template>
        <template v-slot:job-details
          ><i class="far fa-address-card"></i>Lorem ipsum dolor sit amet
          consectetur adipisicing elit. Placeat unde quas beatae impedit
          aspernatur illum voluptate, praesentium dignissimos in minima aperiam
          debitis excepturi. Mollitia soluta, delectus obcaecati aut eius
          placeat!</template
        >
        <template v-slot:job-title>Data Scientist</template>
      </card>
      <!-- CARD END -->
      <card>
        <template v-slot:company-logo>
          <Logo class="w-full m-auto" />
        </template>
        <template v-slot:company-name> TheLEAD.io | LEAD </template>
        <template v-slot:job-details
          >Lorem ipsum dolor sit amet consectetur adipisicing elit. Placeat unde
          quas beatae impedit aspernatur illum voluptate, praesentium
          dignissimos in minima aperiam debitis excepturi. Mollitia soluta,
          delectus obcaecati aut eius placeat!</template
        >
        <template v-slot:job-title>Instructor</template>
      </card>
      <card>
        <template v-slot:company-logo>
          <Logo class="w-full m-auto" />
        </template>
        <template v-slot:company-name> TheLEAD.io | LEAD </template>
        <template v-slot:job-details
          >Lorem ipsum dolor sit amet consectetur adipisicing elit. Placeat unde
          quas beatae impedit aspernatur illum voluptate, praesentium
          dignissimos in minima aperiam debitis excepturi. Mollitia soluta,
          delectus obcaecati aut eius placeat!</template
        >
        <template v-slot:job-title>Instructor</template>
      </card>
      <card>
        <template v-slot:company-logo>
          <Logo class="w-full m-auto" />
        </template>
        <template v-slot:company-name> TheLEAD.io | LEAD </template>
        <template v-slot:job-details
          >Lorem ipsum dolor sit amet consectetur adipisicing elit. Placeat unde
          quas beatae impedit aspernatur illum voluptate, praesentium
          dignissimos in minima aperiam debitis excepturi. Mollitia soluta,
          delectus obcaecati aut eius placeat!</template
        >
        <template v-slot:job-title>Instructor</template>
      </card>
      <card>
        <template v-slot:company-logo>
          <Logo class="w-full m-auto" />
        </template>
        <template v-slot:company-name> TheLEAD.io | LEAD </template>
        <template v-slot:job-details
          >Lorem ipsum dolor sit amet consectetur adipisicing elit. Placeat unde
          quas beatae impedit aspernatur illum voluptate, praesentium
          dignissimos in minima aperiam debitis excepturi. Mollitia soluta,
          delectus obcaecati aut eius placeat!</template
        >
        <template v-slot:job-title>Instructor</template>
      </card>
    </div>
  </div>
</template>

<script>
export default {};
</script>
