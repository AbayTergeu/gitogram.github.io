<template>
    <div class="c-topline">
        <div class="x-container">
            <div class="headline">
                <slot name="headline"/>
            </div>
            <div class="content">
                <slot name="content"/>
            </div>
        </div>
    </div>
</template>

<style lang="scss" src="./topline.scss" scoped></style>