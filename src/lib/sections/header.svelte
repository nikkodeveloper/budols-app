<script lang="ts">
    import logo from "$lib/assets/budols-logo-primary.webp"
    import { Button } from "$lib/components/ui/button/index.js";
</script>

<header class="mb-6 bg-neutral-950 shadow-lg border-b border-neutral-900">
    <div class="header-inner  lg:max-w-4xl flex justify-between items-center mx-auto h-14">
        <div class="flex gap-4">
            <div class="logo-wrap flex items-center">
                <a href="#">
                    <img src="{logo}" alt="budols-logo" />
                </a>
            </div>
            <nav class="flex gap-1 items-center text-neutral-300 text-sm ">
                <a href="#" class="py-4 px-4"><span class="drop-shadow">Home</span></a>
                <a href="#" class="py-4 px-4">Categories</a>
                <a href="#" class="py-4 px-4">About Us</a>
            </nav>
        </div>
        <Button href="#" class="bg-neutral-950 hover:bg-green-2222 hover:border-green-2222 border border-neutral-600 flex gap-2">
            <iconify-icon icon="game-icons:banana-peeled" width="20" height="20" class="text-yellow-400 drop-shadow-md"></iconify-icon>
            <span class="drop-shadow-md">Explore Top Budols</span>
        </Button>
    </div>
</header>