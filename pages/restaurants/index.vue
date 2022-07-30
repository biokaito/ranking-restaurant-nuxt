<template>
  <div>
    <Html :lang="dynamic > 50 ? 'en-GB' : 'en-US'">
      <Head>
        <Title>Top 50 ranking restaurants</Title>
        <Meta name="description" content="My page is cool" />
        <Link rel="preload" href="https://picsum.photos" as="scrit" />
      </Head>
    </Html>
    <NuxtLayout name="custom">
      <div class="container">
        <RestaurantTable />
      </div>
    </NuxtLayout>
  </div>
</template>
