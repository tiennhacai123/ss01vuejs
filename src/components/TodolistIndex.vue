<template>
  <div>
    <section class="vh-100 gradient-custom">
      <div class="container py-5 h-100">
        <div class="row d-flex justify-content-center align-items-center h-100">
          <div class="col col-xl-10">
            <div class="card">
              <div class="card-body p-5">
                <h3 style="text-align: center; margin-bottom: 40px">
                  Quản lý công việc
                </h3>
                <addJobVue></addJobVue>

                <!-- Tabs navs -->
                <ul class="nav nav-tabs mb-4 pb-2" id="ex1" role="tablist">
                  <li class="nav-item" role="presentation">
                    <a class="nav-link active">Tất cả công việc</a>
                  </li>
                </ul>
                <!-- Tabs navs -->

                <!-- Tabs content -->
                <tabContentVue></tabContentVue>
                <!-- Tabs content -->
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<script setup>
import addJobVue from "./bt10/addJob.vue";
import tabContentVue from "./bt10/tabContent.vue";
</script>

<style></style>