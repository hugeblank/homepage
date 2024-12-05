<script>
    import Badge from "$lib/Badge.svelte";
    import Social from "$lib/Social.svelte";
</script>

<div class="flex flex-col text-center place-content-center">
    <div class="flex flex-row place-content-center gap-3">
        <img class="w-10 h-10 self-center" src="favicon.png" alt="A bagel">
        <h1>Welcome to </h1>
        <h1 title="you are here">hugeblank.dev</h1>
        <img class="w-10 h-10 self-center" src="favicon.png" alt="A bagel">
    </div>
    <p>Important Viewing:</p>
    <video controls class="min-w-1/6 ml-auto mr-auto">
        <source src="nene~yayboom.mp4" type="video/mp4"/>
        <track src="nene~yayboom.vtt" kind="captions">
    </video>
    <h2 class="pt-4">Hello</h2>
    <p class="w-3/5 mr-auto ml-auto">
        I'm hugeblank, or Todd depending on the time of day and who you ask. 
        I have a bachelors degree in CS and use my skills in ways that would make my professors wish they didn't let me graduate.
        I spend most of my time programming in Java, but got my degree using other languages like C/C++, Python, and frameworks like Flutter and Django.
        Recently I've been dipping my toe into web development via typescript, and most recently with Svelte.
        I'd like to get a job so if you're hiring shoot me an email or something.
    </p>
    <p class="w-3/5 mr-auto ml-auto">
        Over the last few years I've also gained an unhealthy obsession over public transit (trains), <a class="text-cyan-600 hover:underline" href="https://baub.au">vTubers</a>, and Japanese culture, and even the language itself. 
        This obsession has (naturally) resulted in me learning Japanese and going on a 2 month trip to Japan, where I visited over 20 cities and made over <a id="oops" href="#oops" title="I forgot one already" class="line-through">20</a> 19 memories.
        I will definitely be making a blog post about that so please stay tuned.
    </p>
    <h2 class="pt-4">I have a blog</h2>
    <p><a href="https://blog.hugeblank.dev/" class="text-cyan-600 hover:underline">it is here</a>.</p>
    <h2 class="pt-4">I have projects</h2>
    <p>Like this Minecraft mod that embeds a Lua interpreter to allow you to write Lua mods. <a href="https://github.com/Moonflower-Mods/allium" class="text-cyan-600 hover:underline">it is here</a>.</p>
    <p>Or this other mod that fixes Minecraft's daylight cycle skipping when on a laggy server. <a href="https://modrinth.com/mod/asahi" class="text-cyan-600 hover:underline">it is here</a>.</p>
    <p>Or my blog which is actually a custom frontend for <a href="https://whtwnd.com" class="text-cyan-600 hover:underline">WhiteWind</a>, a blog service that utilizes <a href="https://atproto.com" class="text-cyan-600 hover:underline">ATProto</a>. <a href="https://github.com/hugeblank/whitebreeze" class="text-cyan-600 hover:underline">it is WhiteBreeze</a>.</p>
    <h2 class="pt-4">I have social media</h2>
    <div class="mr-auto ml-auto grid grid-cols-2 gap-2">
        <Social href="https://github.com/hugeblank/" src="github.svg" alt="GitHub" username="@hugeblank"/>
        <Social href="https://bsky.hugeblank.dev/" src="bluesky.png" alt="Bluesky" username="@hugeblank.dev"/>
        <Social src="signal.png" alt="Signal" username="@hugeblank.01"/>
        <Social src="discord.png" alt="Discord" username="@hugeblank"/>
        <Social href="https://steamcommunity.com/id/hugeblank/" src="steam.ico" alt="Steam" username="hugeblank"/>
        <Social href="mailto:hugeblank@gmail.com" src="email.png" alt="Email" username="hugeblank@gmail.com"/>
    </div>
    <h2 class="pt-4 ">The badges</h2>
    <div class="mr-auto ml-auto grid grid-cols-3 gap-y-2 pt-2">
        <Badge site="aspenr.dev"/>
        <Badge site="ally.cat" type="png"/>
        <Badge site="danii.fi"/>
        <Badge href="github.com/tmpim" site="tmpim.pw" alt="tmpim.pw badge" type="png" full=true/>
        <Badge site="kotahu.com"/>
        <Badge site="archlinux.org"/>
        <!-- Other badges go above --> 
        <p>My badge:</p><Badge href="hugeblank.dev" site="hugeblank.dev" alt="The official hugeblank.dev badge" full=true/>
    </div>
    <h2 class="pt-4">Bagel lore</h2>
    <h3 class="pt-2">The name</h3>
    <p class="w-3/5 mr-auto ml-auto">
        The name "hugeblank" dates back to 2010 when I was in my local library, signing up for Roblox. I had a few criteria for the name.
        I didn't want it to have any numbers, and I wanted it to be comprised of real words. That made things difficult enough, 
        but to top it all off Roblox was already really popular back then, despite it being entirely different from what it is now.
        The only saving grace for me was that below the username box, if you put in a username that already existed,
        it would provide a few alternatives that weren't already taken. I spent what felt like an eternity typing combinations of words in with no luck whatsoever.
        It got to the point that I gave up and just slammed the keyboard and got a bunch of gibberish which was, hilariously, taken.
        But whatever keysmash I threw in opened the username suggestion area's third eye. Up until now it had just been putting numbers onto what I wrote in, but
        this time, it came close to the answer. hugeblank0. I took that username, put it in the input box, and then removed the 0 and prayed. 
        It worked, I signed up, and the rest is history.
    </p>
    <h3 class="pt-2">The bagel</h3>
    <p class="w-3/5 mr-auto ml-auto">
        The bagel motif was a later occurence in the hugeblank lore. It happened due to a user in a Minecraft server I was playing on back in 2014. 
        They were messing with anagrams of other online players usernames and eventually got to me. They landed on "bagel hunk" which I thought was funny.
        At that time I didn't exactly have a profile icon I was set on using, so I went and googled a photo of a bagel, and found this one:
    </p>
    <img class="min-w-1/6 ml-auto mr-auto" src="images/hugeblank.png" alt="Watercolor Rendering of a plain bagel by Judy Unger" title="Watercolor Rendering of a plain bagel by Judy Unger"/>
    <p class="w-3/5 mr-auto ml-auto">
        While working on this website I decided to finally see if I could find the source, and with relative ease I was able to.
        Please enjoy Judy Unger's blog, <a href="https://foodartist.wordpress.com/2011/02/23/41-i-had-a-hole-lox-of-fun-illustrating-bagels/">Illustrating My Life #41</a>
        It surprised me to find out that what I had been using this whole time was an illustration, and not a photo. Her work is incredibly impressive and when I have the free time
        I will be spending it reading through and admiring her images.
    </p>
</div>