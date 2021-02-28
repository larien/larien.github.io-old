<template>
    <div class="button">
        <!-- https://iconscout.com/icon/email-3315713 -->
        <a><svg xmlns="http://www.w3.org/2000/svg" width="100%" height="100%" viewBox="-4 -5 40 40"><path d="M27,4.70996H5c-2.47998,0-4.5,2.02002-4.5,4.5v13.58002c0,2.47998,2.02002,4.5,4.5,4.5h22c2.47998,0,4.5-2.02002,4.5-4.5V9.20996C31.5,6.72998,29.47998,4.70996,27,4.70996z M28.5,22.78998c0,0.83002-0.66998,1.5-1.5,1.5H5c-0.83002,0-1.5-0.66998-1.5-1.5V9.29999l9.71002,7.66998C14.03003,17.62,15.02002,17.94,16,17.94s1.96997-0.32001,2.78998-0.97003L28.5,9.31V22.78998z"/></svg></a>
    </div>
</template>

<script>
export default {
    props: {
        colorHex: {
            type: String,
            required: true
        },
        icon: {
            type: String,
            required: true
        }
    },
    data(){
        return {
            color: "#fff"
        }
    }
}
</script>

<style scoped>
.button {
    height: 100%;
    width: 100%;
    border-radius: 10px;
    cursor: pointer;
    margin: 10px;
}
.button:hover {
    background-color: orange;
}
svg {
  fill: rgb(190, 190, 190);
}
svg:hover {
  fill: black;
}
</style>