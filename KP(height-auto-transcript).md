<div>
      not very long ago i put out a quick video taking a look at the differences
      between width auto and width 100 one of the things that caught me off
      guard with it was in the comments how many people were asking about how
      height auto works were the differences between height auto and height 100
      percent so instead of trying to answer all those comments i said why not
      just make a video on it so here we are um so the very first thing i want
      to look at and maybe the thing that throws people off the most is when you
      have a div let's say like here i put a height of 100 on it but it's not
      actually changing and if you're doing heights as a percentage same as
      width you have to be thinking what's the height of you know what it's all
      what is that of so the percentages are always based on the containing
      block which most of the time is the parent and i won't get into the
      differences between those right now um but most of the time a containing
      block is the parent and so the height here of 100 is 100 of the body but
      because i don't have a lot of content on my page the body is actually
      really small and not everyone realizes that because if you do come and put
      a background on your body let's just do a pink background on here um the
      whole viewport will fill with that color even though you can see here i
      have a border on it on the body and the body's staying small so this the
      background on the body changing the color isn't only going on there it's
      actually filling up the whole viewport uh it's filling up the whole
      viewport or the whole page if you have scrolling so that is just something
      to be aware of and let's get rid of that pink background now because we
      won't be needing it um and that should disappear there we go and we can
      see that we have that red border there so that's my body so if i go on my
      body now and i say that the height is let's say 100 pixels that means the
      body is going to grow and this with the dark background is growing to fit
      it because the height is a hundred percent if i do a fifty percent height
      the height is now fifty percent of that so whatever this is let's make it
      a bit bigger to make it stand out more we can see that it's growing to
      fifty percent of the height of the body so remember the percentage on a
      height is always percentage of the parent so it depends or the containing
      block if you're using position absolute in different things sometimes that
      can be a little different but keeping it simple for now just think of it
      as most of the time being the height of the parent where height auto comes
      into play so if i do a height auto on there you'll see it shrinks down to
      fit the content and unlike a width of auto which is trying to be the width
      of the viewport a height of auto will actually be 0 pixels tall so if i
      remove all the content from my example div here there's no content in it i
      can't see anything uh it just it vanishes because it's literally zero
      pixels tall because the there's no content there's no height and then as
      we add content to it so i can put my hello world back it grows a little
      bit and that div grows to fit the height of the content that's inside of
      it and this is a wonderful behavior that we don't want to get rid of
      because that means as i add more content let's just add a bunch of filler
      text here and that should give us some words and we'll see that this is
      growing so the height of this is adjusted to that content by relying on a
      height of auto it just means that the element itself is going to
      automatically adjust to whatever we're placing in there and most of the
      time that's what we want now this will change if you're in a flex or grid
      in those situations they're no longer block elements they're going to be
      flex items or grid items which those behaviors change a bit something we
      can look at in the future but here just to show you that the default is to
      grow or to shrink based on the content inside of it and that's always a
      good thing because if you do set a height let's just say i said height
      auto or height let's do 500 pixels this time so it's going to overflow out
      the body which is kind of awkward but let's just say i came in here with a
      lot of text let's delete that or come to my hello world and let's add like
      lorem i don't know 100 words 100 should be enough um and those words oh
      not not enough laura let's add another 100 words and now what's gonna
      happen is it's spilling out the bottom because it's not growing to
      accommodate the content that's inside of it it's now stuck at 100 pixels
      and it will never grow i do get asked a lot about this and on setting
      heights and things like that so my advice is always try not to set a
      height if you don't need to set a height heights are very very dangerous
      for this but one thing if you do really need a height you can always do a
      min height so the advantage with the min height is it will grow to fit the
      content if there's too much content but if there's not too much content
      let's just go back to my hello world when we have just the hello world
      it's gonna stop like the minimum the smallest it can get is 500 and
      another advantage with this is let's go back up to like lorem 100 where we
      had empty room this also makes responsive websites a lot easier because
      when we have a big screen the content has more room to live but when we
      get to smaller screen sizes that content has less and less room to live
      and it gets longer and longer and longer so by setting a min height here
      you can see it's growing when it has to but at this size it maintains that
      height right there and this doesn't have to be this could even be viewport
      50 viewport height so it's a minimum of half my viewport but if it needs
      more space it can get more space or if it goes the other way then it locks
      in at that size whereas if we just set this again as a height and now it
      looks great at big screens but when we get to the small screens oh no we
      run into trouble where content is overflowing so in general i try and
      leave height at auto try never to touch it but if i do need to touch it
      most of the time i'm going to set a minimum height and in very very very
      rare situations maybe you actually set a solid height on something but i
      find most of the time it's something that i don't i can avoid unless it's
      like a pseudo element or something where it's really for decorational
      purposes if you didn't see my video on how widths work with auto and all
      of that you can check that one out i've linked to it in the description
      down below and if you want to know how the lorem thing there worked and
      why that was generating content i do have a video that looks at how emmet
      works and some really awesome shortcuts you can be using it so that one is
      linked in the description below and you should see a card or something
      popping up on the screen for it now thank you very much for watching i
      really do hope that you enjoyed it and learned something along the way a
      really big thank you to my patrons for their support each and every month
      with a special thank you to zach who is my enabler of awesome and of
      course until next time don't forget to make your corn on the internet just
      a little bit more awesome
    </div>