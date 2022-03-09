<template>
  <AsCard blue landscape>
    <AsCardSection class="as-py-32" first>
      <h2 class="as-text-16-semibold">PHP X-Ray</h2>
      <p class="as-mt-8 as-text-28-bold">Cek dan Tingkatkan Performa Website Anda</p>
      <p class="as-mt-16 as-text-16">Dapatkan informasi detail tentang performa website Anda sekaligus bagaimana meningkatkan performa website Anda</p>
      <AsButton class="as-mt-32" primary withIcon><span>Tingkatkan</span><i class="as-icon-arrow-right"></i></AsButton>
    </AsCardSection>
    <AsCardSection illustration>
      <AsImage alt="PHP X Ray" fluid src="https://niagaspace.sgp1.cdn.digitaloceanspaces.com/event/images/nh-event-event-1646800519-illustrationphpxray.svg"/>
    </AsCardSection>
  </AsCard>
</template>

<script setup>
  import {
    AsButton,
    AsCard,
    AsCardSection,
    AsImage,
  } from '@niagahoster/components'
</script>
