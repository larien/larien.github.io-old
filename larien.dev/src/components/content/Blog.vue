<template>
    <div class="button">
        <!-- https://iconscout.com/icon/newspaper-164 -->
        <a><svg xmlns="http://www.w3.org/2000/svg" width="100%" height="100%" viewBox="-6 -6 35 35"><path d="M20 22H4c-2.2 0-4-1.8-4-4V3c0-.6.4-1 1-1h19c.6 0 1 .4 1 1v14c0 .6-.4 1-1 1s-1-.4-1-1V4H2v14c0 1.1.9 2 2 2h16c.6 0 1 .4 1 1s-.4 1-1 1z"/><path d="M12 4c-.6 0-1-.4-1-1s.4-1 1-1 1 .4 1 1-.4 1-1 1zm8 18h-5c-.6 0-1-.4-1-1s.4-1 1-1h5c1.1 0 2-.9 2-2V6h-2c-.6 0-1-.4-1-1s.4-1 1-1h3c.6 0 1 .4 1 1v13c0 2.2-1.8 4-4 4zm-10-8H5c-.6 0-1-.4-1-1V7c0-.6.4-1 1-1h5c.6 0 1 .4 1 1v6c0 .6-.4 1-1 1zm-4-2h3V8H6v4zm10-4h-3c-.6 0-1-.4-1-1s.4-1 1-1h3c.6 0 1 .4 1 1s-.4 1-1 1zm0 3h-3c-.6 0-1-.4-1-1s.4-1 1-1h3c.6 0 1 .4 1 1s-.4 1-1 1z"/><path d="M16 14h-3c-.6 0-1-.4-1-1s.4-1 1-1h3c.6 0 1 .4 1 1s-.4 1-1 1zm0 4H5c-.6 0-1-.4-1-1s.4-1 1-1h11c.6 0 1 .4 1 1s-.4 1-1 1z"/><metadata><rdf:RDF xmlns:rdf="http://www.w3.org/1999/02/22-rdf-syntax-ns#" xmlns:rdfs="http://www.w3.org/2000/01/rdf-schema#" xmlns:dc="http://purl.org/dc/elements/1.1/"><rdf:Description about="https://iconscout.com/legal#licenses" dc:title="newspaper" dc:description="newspaper" dc:publisher="Iconscout" dc:date="2017-09-14" dc:format="image/svg+xml" dc:language="en"><dc:creator><rdf:Bag><rdf:li>Cosmin Negoita</rdf:li></rdf:Bag></dc:creator></rdf:Description></rdf:RDF></metadata></svg></a>
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
    transition: 0.3s;
}
.button:hover {
    background-color: #1da1eb;
    opacity: 1;
}
svg {
  fill: rgb(190, 190, 190);
}
svg:hover {
  fill: white;
}
</style>