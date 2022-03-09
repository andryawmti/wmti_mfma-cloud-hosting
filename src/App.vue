<template>
    <AsLayout>
      <div class="container">
        <div class="grid">
          <AsCardServiceSelect class="g-col-12 g-col-lg-4"/>
          <AsCardServiceRenew 
            class="g-col-12 g-col-lg-4"
            expiresAt="23 Februari 2023"
            timeLeft="8 bulan 13 hari"
          />
          <AsCardServiceUpgrade 
            class="g-col-12 g-col-lg-4"
            productTitle="Paket Personal Unlimited Hosting"
            productUrl="#"
          />
        </div>
        <PhpXray class="as-mt-48"/>
        <div class="as-mt-44 grid">
          <AsCardInstallCms class="g-col-12 g-col-lg-6"/>
          <AsCardFileManager class="g-col-12 g-col-lg-6"/>
        </div>
        <div class="as-mt-48 grid">
          <div class="g-col-12 g-col-lg-8">
            <AsCardCpanelShortcuts/>
            <AsCardResourceInfo class="as-mt-48"/>
            <AsCardBuySsl class="as-mt-48"/>
          </div>
          <div class="g-col-12 g-col-lg-4">
            <AsCardHostingDetail/>
            <AsCardCpanelAccount class="as-mt-48"/>
            <AsCardFeatureRequest class="as-mt-48"/>
          </div>
        </div>
        <hr class="as-mt-48" style="border: 1px solid #D0D0D0;">
        <AsSectionCourse :courses="courses" class="as-mt-64"/>
      </div>
    </AsLayout>
</template>

<script setup>
  import {
    AsLayout,
    AsSectionCourse,
    AsCardCpanelAccount,
    AsCardCpanelShortcuts,
    AsCardHostingDetail,
    AsCardFeatureRequest,
    AsCardInstallCms,
    AsCardFileManager,
    AsCardBuySsl,
    AsCardResourceInfo,
    AsCardServiceRenew,
    AsCardServiceSelect,
    AsCardServiceUpgrade,
  } from '@niagahoster/components'

  import PhpXray from './components/PhpXray.vue'

  const courses = [
    {
      authorName: 'Akrilvha D Wiervi',
      authorPicture: 'https://niagaspace.sgp1.cdn.digitaloceanspaces.com/event/images/nh-event-event-1646725100-profilepicture.png',
      authorRole: 'Product Manager at Niagahoster',
      thumbnail: 'https://niagaspace.sgp1.cdn.digitaloceanspaces.com/event/images/nh-event-event-1646724887-thumbnailcourse.svg',
      thumbnailAlt: 'CourseThumbnail',
      title: 'Mengenal Lebih Jauh Tentang cPanel',
    },
    {
      authorName: 'Akrilvha D Wiervi',
      authorPicture: 'https://niagaspace.sgp1.cdn.digitaloceanspaces.com/event/images/nh-event-event-1646725100-profilepicture.png',
      authorRole: 'Product Manager at Niagahoster',
      thumbnail: 'https://niagaspace.sgp1.cdn.digitaloceanspaces.com/event/images/nh-event-event-1646724887-thumbnailcourse.svg',
      thumbnailAlt: 'CourseThumbnail',
      title: 'Belajar WordPress untuk Pemula',
    },
    {
      authorName: 'Akrilvha D Wiervi',
      authorPicture: 'https://niagaspace.sgp1.cdn.digitaloceanspaces.com/event/images/nh-event-event-1646725100-profilepicture.png',
      authorRole: 'Product Manager at Niagahoster',
      thumbnail: 'https://niagaspace.sgp1.cdn.digitaloceanspaces.com/event/images/nh-event-event-1646724887-thumbnailcourse.svg',
      thumbnailAlt: 'CourseThumbnail',
      title: 'Membuat Landing Page dengan Elementor',
    },
  ]
</script>
