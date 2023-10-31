<template>
    <section id="sliderType" :class="['slider__wrap', element]">
        <h2 class="blind">{{ title }}</h2>
        <div class="slider__inner">
            <div class="slider">
                <div class="slider__img">
                    <div class="desc">
                        <span>developper</span>
                        <h3>new Project</h3>
                        <p>
                            디자인 실력 향상시키자!<br>
                            여러 포트폴리오 도전하자
                        </p>
                        <div class="btn">
                            <a href="/">자세히 보기</a>
                            <a href="/" class="black">사이트 보기</a>
                        </div>
                    </div>
                </div>
                <div class="slider__arrow">
                    <a href="/" class="left"><span class="ir">이전 이미지</span></a>
                    <a href="/" class="right"><span class="ir">다음 이미지</span></a>
                </div>
                <div class="slider__dot">
                    <a href="/" class="dot"><span class="ir">1</span></a>
                    <a href="/" class="dot"><span class="ir">2</span></a>
                    <a href="/" class="dot"><span class="ir">3</span></a>
                    <a href="/" class="play"><span class="ir">플레이</span></a>
                    <a href="/" class="stop"><span class="ir">정지</span></a>
                </div>
            </div>

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