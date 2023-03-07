<template lang="">
    <div>
        <div class="flex justify-center" id="three"></div>    
    </div>
</template>
<script>
import * as THREE from 'three';

export default {
    name: "Three",
    setup() {
        const scene = new THREE.Scene();
        scene.background = new THREE.Color(0xe6eaeb);
        const camera = new THREE.PerspectiveCamera( 30, window.innerWidth / window.innerHeight, 0.1, 1000);
        const renderer = new THREE.WebGLRenderer();
        renderer.setSize( 800, 600 );
        document.body.appendChild( renderer.domElement );
        const geometry = new THREE.BoxGeometry();
        const material = new THREE.MeshBasicMaterial( { color: 0x38352d } );
        const cube = new THREE.Mesh( geometry, material );
        scene.add( cube );
        camera.position.z = 5;
        


        
        const animate = function () {
            requestAnimationFrame( animate );
            cube.rotation.x += 0.01;
            cube.rotation.y += 0.01;
            renderer.render( scene, camera );
        };
        animate();
    }   
}
</script>
<style lang="">
    
</style>
