<script>

</script>

<svelte:head>
	<link href="https://fonts.googleapis.com/css?family=Inter:300&display=swap" rel="stylesheet">
</svelte:head>

<style>

h1, h2, h3, p{
    font-family: 'Inter', sans-serif;
    
    color: #ffffff;
}

h1{
    
    text-transform: uppercase;
    font-weight: 600;
    font-size: calc(0.75em + 1vmin);
}

h2, p{
    font-weight: 300;
    font-size: calc(0.5em + 0.75vmin);
}

h2{
    font-weight: 300;
    font-size: calc(0.5em + 0.75vmin);
    margin-top: 16px;
    margin-bottom: 24px;
}


h3{
    font-size: calc(0.25em + 0.5vmin);
    font-weight: lighter;
}

.list-row-wrapper{
    display: inline-block;
}

.gutter-linespace{
    padding-bottom: 4px;
}
.gutter-topic{
    padding-top: 33.3%;
}

.list-row-wrapper .detail-space{
    margin-top: 0;
    margin-bottom: 0px;
}

.list-column-wrapper div{
    margin: 0;

}

.list-number{
    position: absolute;
    margin: 0;
}

.detail-space{
    margin-left: calc(3em + 0.25vmin);
}

.detail-content{
    margin-left: 14.6%;
    margin-right: 10.9%;
    margin-top: 30%;
}

.detail-content-wrapper{
    
    background-color: #000000;
    max-height: 100%;
    max-width: 100%;
    order: 2;
}

.content-col{
    flex: 1;
}
</style>


<div class="content-col detail-content-wrapper">
    <div class="detail-content gutter-topic">
        <h1>Software &<br>Embedded System Engineer</h1>

        <h2 class="detail-space gutter-topic">1. PROFILE</h2>

        <p>Byounghern Joe Kim is a software and embedded system engineer based in Ulsan, South Korea.
He currently works at UNIST as a researcher. He enjoys working on development of product-service system idea with good friends.</p>

        <h2 class="detail-space gutter-topic">2. RECOGNITION<br>(5 ITEMS)</h2>

        <div class="list-column-wrapper">
        <div>
            <div class="list-row-wrapper gutter-linespace">
                <p class="list-number">i.</p><p class="detail-space">Startup Experiences (6)</p>
            </div>
        </div>

        <div>
            <div class="list-row-wrapper gutter-linespace">
                <p class="list-number">ii.</p><p class="detail-space">Patents (6)</p>
            </div>
        </div>

        <div>

            <div class="list-row-wrapper gutter-linespace">
                <p class="list-number">iii.</p><p class="detail-space">Research (4)</p>
            </div>
        </div>

        <div>
            <div class="list-row-wrapper gutter-linespace">
                <p class="list-number">iv.</p><p class="detail-space">Product & Service Development Projects (20)</p>
            </div>
        </div>

        <div>
            <div class="list-row-wrapper gutter-linespace">
                <p class="list-number">v.</p><p class="detail-space">IT Lecturer (10)</p>
            </div>
        
        </div>
        </div>
        

        <h2 class="detail-space gutter-topic">3. ASSOCIATED GROUPS</h2>

        <p>Design & Electronic Convergence System Lab, UNIST.</p>
        <p>POSTECH Creative Entrepreneur Omphalos</p>
        <p>Softwarer Maestro</p>


        <h2 class="detail-space gutter-topic">4. CONTACT</h2>

        <p>Instagram</p>
        <p>E-Mail</p>


        <div class="gutter-topic">
            <h3>Location<i/>Ulsan, South Korea.</h3>
        </div>
    </div>

</div>