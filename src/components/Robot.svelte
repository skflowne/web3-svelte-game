<script>
    /*
    DNA
    
  */
    export let monster
    const { dna } = monster
    const head = (parseInt(dna.substring(0, 2)) % 2) + 1
    const body = (parseInt(dna.substring(2, 4)) % 2) + 1
</script>

<div class="robot">
    <img class="head" src={`images/robot/heads/head_${head}.png`} alt="head" />
    <img class="body" src={`/images/robot/bodies/body_${body}.png`} alt="body" />
</div>
