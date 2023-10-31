<template>
    <section id="bannerType" :class="['banner__wrap', element]">
        <h2 class="blind"></h2>
        <div class="banner__inner">
            <h3 class="title">{{ title }}</h3>
            <p class="desc">
                더 다양한 강의는 유튜브를 통해 제공하고 있습니다.
                <a href="/" title="유튜브 페이지 이동">youtube.com/c/Webstoryboy</a>
            </p>
            <p class="small">배너 유형 01</p>
        </div>
    </section>
</template>

<script>
export default {
    props: {
        element: String,
        title: String,
    }
}
</script>