<script setup lang="ts">
import { ModalDemo } from '#components'

const modal = useModal();
const router = useRouter();
const auth = useAuthStore();

function openDemoModal() {
  modal.open(ModalDemo)
}
</script>

<template>
  <div class="grid grid-cols-12 gap-6">
    <div class="col-span-12 lg:col-span-3">
<!--      <UCard>-->
<!--        <div class="flex gap-3">-->
<!--          <UButton label="Modal" @click="openDemoModal" color="gray" />-->
<!--          <UButton label="404 page" color="gray" @click="router.push('/404')" />-->
<!--        </div>-->
<!--      </UCard>-->
    </div>
    <div class="col-span-12 lg:col-span-9">
<!--      <UCard>-->
<!--        <pre>{{ auth.user }}</pre>-->
<!--      </UCard>-->
      <h1>DASHBOARD</h1>
    </div>
  </div>
</template>
