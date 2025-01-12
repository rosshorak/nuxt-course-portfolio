<template>
    <article class="prose dark:prose-invert max-w-none">
        <div class="my-12 inline-block">
            <p class="highlight highlight-yellow">Messing around with pull requests and changes</p>
            <p class="highlight highlight-green">Green highlight notice</p>
            <p class="highlight highlight-purple">Purple notice on new branch</p>
        </div>
        <ContentDoc path="/"/>
    </article>
</template>

<style>
.highlight {
    padding: 5px 15px;
    border-radius: 8px;
}
.highlight-yellow {
    background-color: yellow;
}
.highlight-green {
    background-color: green;
    color: white;
}
.highlight-purple {
    background-color: purple;
    color: white;
}
</style>