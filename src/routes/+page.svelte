<script>
    import Button from "$lib/Button.svelte";
    import Social from "$lib/Social.svelte";
</script>

<div class="flex flex-col text-center place-content-center">
    <div class="flex flex-row place-content-center gap-3">
        <img class="w-10 h-10 self-center" src="favicon.png" alt="A bagel">
        <h1>Welcome to <p title="you are here">hugeblank.dev</p></h1>
        <img class="w-10 h-10 self-center" src="favicon.png" alt="A bagel">
    </div>
    <p>Important Viewing:</p>
    <video controls class="min-w-1/6 ml-auto mr-auto">
        <source src="nene~yayboom.mp4" type="video/mp4"/>
        <track src="nene~yayboom.vtt" kind="captions">
    </video>
    <h2 class="pt-4">Hello</h2>
    <p class="lg:w-3/5 mr-auto ml-auto">
        I'm hugeblank, or Todd depending on the time of day and who you ask. 
        I have a bachelors degree in CS and use my skills in ways that would make my professors wish they didn't let me graduate.
        I spend most of my time programming in Java, but got my degree using other languages like C/C++, Python, and frameworks like Flutter and Django.
        Recently I've been dipping my toe into web development via typescript, and most recently with Svelte.
        I'd like to get a job so if you're hiring shoot me an email or something.
    </p>
    <p class="lg:w-3/5 mr-auto ml-auto">
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
    <h2 class="pt-4 ">The buttons</h2>
    <div class="mr-auto ml-auto grid grid-cols-3 gap-y-2 pt-2">
        <Button site="aspenr.dev"/>
        <Button site="ally.cat" type="png"/>
        <Button site="danii.fi"/>
        <Button href="github.com/tmpim" site="tmpim.pw" alt="tmpim.pw button" type="png" full=true/>
        <Button site="kotahu.com"/>
        <Button site="archlinux.org"/>
        <!-- Other buttons go above --> 
        <p>My button:</p><Button href="hugeblank.dev" site="hugeblank.dev" alt="The official hugeblank.dev button" full=true/>
    </div>
    <h2 class="pt-4">Bagel lore</h2>
    <h3 class="pt-2">The name</h3>
    <p class="lg:w-3/5 mr-auto ml-auto">
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
    <p class="lg:w-3/5 mr-auto ml-auto">
        The bagel motif was a later occurence in the hugeblank lore. It happened due to a user in a Minecraft server I was playing on back in 2014. 
        They were messing with anagrams of other online players usernames and eventually got to me. They landed on "bagel hunk" which I thought was funny.
        At that time I didn't exactly have a profile icon I was set on using, so I went and googled a photo of a bagel, and found this one:
    </p>
    <a class="ml-auto mr-auto" href="bagel.png"><img class="w-64" src="bagel.png" alt="Watercolor Rendering of a plain bagel by Judy Unger" title="(click to open) Watercolor Rendering of a plain bagel by Judy Unger"/></a>
    <p class="lg:w-3/5 mr-auto ml-auto">
        While working on this website I decided to finally see if I could find the source, and with a reverse image search I was able to. 
        I had initially thought that the image was lost media, so was very happy to have been able to track it down.
        Not only that, but the bagel wasn't a photo at all, it was an illustration, done by a woman named Judy Unger.
        Judy was a professional illustrator who had done commission work for food companies like Del Monte, Kirkland, Little Debbie, and Meow Mix cat food.
        I have an appreciation for artists and firmly believe that their work should be properly attributed and compensated if necessary, so I reached out to her about the story of how I ended up
        with the bagel motif and how her illustration ended up being my profile picture for the last decade. I continued by asking her for a way to obtain a license to use the image,
        in hopes that she might respond so I could rest easy knowing I'm using it fairly. To my delight she replied with a similar gratitude for me even bothering to ask about licensing,
        and gave me a perpetual commercial use license at a discount! The image you see above is the highest resolution publicly available rendering of her watercolor illustration of a plain bagel
        she did for Lender's Manhattan in January of 2003. Please enjoy her blog post 
        <a class="text-cyan-600 hover:underline" href="https://foodartist.wordpress.com/2011/02/23/41-i-had-a-hole-lox-of-fun-illustrating-bagels/">found here</a>, 
        where she talks about the process of the commission, making 15 different bagels, and how the director of the project actually prefered her marker technique over the watercolor version for the plain bagel!
        Her work is incredibly impressive and when I have the free time I will be spending it reading through her blog and admiring the illustrations.
    </p>
</div>