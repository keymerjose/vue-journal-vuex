<template>
    <div class="entry-container mb-3 pointer p-2 " @click="$router.push({ name: 'entry', params: { id: 10 } })">
        <div class="entry-title d-flex">
            <span class="text-success fs-5 fw-bold">15</span>
            <span class="mx-1 fs-5">Julio</span>
            <span class="mx-2 fw-light">2023</span>
        </div>

        <div class="entry-description">
            Proident sunt eu consectetur laborum commodo nostrud velit. Amet ut irure ex voluptate. Proident dolor eiusmod occaecat non ad dolore veniam. Occaecat deserunt officia Lorem ex officia occaecat ipsum voluptate. Occaecat ipsum occaecat aliquip do exercitation fugiat officia id proident exercitation eiusmod.
        </div>
    </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
    .entry-container {
        border-bottom: 1px solid #2c3e50;
        transition: 0.2s all ease-in;

        &:hover {
            background-color: lighten($color: gray, $amount: 0);
            transition: 0.2s all ease-in;
        }
    }
    .entry-description {
        font-size: 12px;
    }
</style>