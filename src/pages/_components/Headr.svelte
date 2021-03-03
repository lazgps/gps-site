<script>
    import { url } from '@roxi/routify';

    console.log("I am in ",$url());
</script>

<style>
</style>

<header>
    <div class="flex flex-row items-center justify-between px-5 md:px-0">
        <a href={$url('/')}>
            <img class="-ml-3" src="/assets/images/logos/logo.png" alt="Our Logo">
        </a>
        <h3 class="font-bold">407.715.2652</h3>
    </div>
</header>
