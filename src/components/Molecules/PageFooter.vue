<script lang="ts">
export default {
    name: "PageFooter"
}
</script>

<template>
    <div class="md:p-20 p-4">

        <div class="grid lg:grid-cols-2 gap-20 lg:gap-0">
            <div class="col-span-1 flex flex-col gap-4">
                <img src="@/assets/masteringlogo.png" class="w-64">
                <p class="text- md:w-96">Sometimes features require a short description. This can be detailed description or
                    just
                    a short text.
                </p>
            </div>
            <div class="col-span-1 grid grid-cols-3">
                <div class="col-span-1 flex flex-col gap-4">
                    <h1 class=" font-bold">Company</h1>
                    <div class="flex flex-col gap-4 text-gray-400">
                        <p>About</p>
                        <p>Community Supports</p>
                        <p>Events</p>
                        <p>Career</p>
                    </div>
                </div>

                <div class="col-span-1 flex flex-col gap-4">
                    <h1 class=" font-bold">Support</h1>
                    <div class="flex flex-col gap-4 text-gray-400">
                        <p>Account</p>
                        <p>Support center </p>
                        <p>FeddBack</p>
                        <p>Contact Us</p>
                    </div>
                </div>

                <div class="col-span-1 flex flex-col gap-4">
                    <h1 class=" font-bold">Resourse</h1>
                    <div class="flex flex-col gap-4 text-gray-400">
                        <p>Help Center</p>
                        <p>Guide</p>
                        <p>Blog</p>
                        <p>Partner Network</p>
                    </div>
                </div>

            </div>

        </div>
    </div>
</template>