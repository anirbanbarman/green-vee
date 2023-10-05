<script>

    import icon1 from '$lib/images/icon1.png';
    import icon2 from '$lib/images/icon2.png';
    import icon3 from '$lib/images/icon3.png';
    import icon4 from '$lib/images/icon4.png';


</script>

<div class="md:fixed absolute md:mr-4 md:right-0 md:top-8 right-12 top-4">
             
    <div class="relative group">
     
        <button class="group-btn" >Anmelden</button>
      
        <ul class="sidebar-menu space-y-9" id="myDropdown">
            <li class="mt-9"><a href="/"><img src={icon1} alt="" /></a></li>
            <li><a href="/"><img src={icon2} alt="" /></a></li>
            <li><a href="/"><img src={icon3} alt="" /></a></li>
            <li><a href="/"><img src={icon4} alt="" /></a></li>
        </ul>
    </div>

</div>