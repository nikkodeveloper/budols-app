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
            <nav class="flex gap-1 items-center text-neutral-300 text-sm">
                <a href="#" class="py-4 px-4 bg-gradient-to-t"><span class="drop-shadow">Home</span></a>
                <a href="#" class="py-4 px-4">Categories</a>
                <a href="#" class="py-4 px-4">About Us</a>
            </nav>
        </div>
        <Button href="#" variant="outline">Explore Top Budols</Button>
    </div>
</header>