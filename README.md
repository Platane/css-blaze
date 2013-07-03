css-blaze is a css trick that emulate a fire over an html element. You should definitively try it, it's pretty cool.


### Usage

Simply paste the css code in your style sheet and add the class name to your element. The element is now burning and your website is 83% cooler.

### Generator

Pink may not be your favorite color? Nevermind I wrote a live editor where you can custom some stuff to make it looks like you want to.

I also made a function that generate colors that look good together, and I made it just for you.

Open the creator.html file, or go to http://platane.github.io/css-blaze to use it.

### CSS code

Past it in your style sheet 

```
.blazing::before{ 
  content:'xlxlx.xlxxxlxlx.xlX..lxlxlLxlxl..Xlx.lxxlxxxxlxXXlXXlxlxlx.xlx.xlxxx.xxlxlx.xlX..lxlxlLxlxl..Xlx.lxxlxxxxlxXXlXXlx.x.xlxxlxx.X.xxlxxlxxlllxxlxlxlxlxlx.xlxxxlxlx.xlX..lxlxlLxlxl..Xlx.lxxlxxxxlxXXlXXlxlxlx.xlx.xlxxx.xxlxlx.xlX..lxlxlLxlxl..Xlx.lxxlxxxxlxXXlXXlx.x.xlxxlxx.X.xxlxxlxxlllxxlxlxlxlxlx.xlxxxlxlx.xlX..lxlxlLxllxxlxxxxlxXXlXXlxlxlx.xlx.xlxxx.xxlxlx.xlX..xlLxlxl..Xlx.lxxlxxxxlxXXlXXlx.x.xlxxlxx.X.xxlxxlxxlllxxlxlxl';
  width:104%;
  left:-2%;
  overflow-x:hidden;
  display:block;
  position:relative;
  font-size:15px;
  font-weight: bold;
  top:-25px; color:rgba(0,0,0,0);
  -moz-animation: blaze infinite 3s;
  -webkit-animation: blaze infinite 3s;
  animation: blaze infinite 3s;
  height:30px; border-radius:5px;
} 
@keyframes blaze { 
 0%{text-shadow:-21.5px 14.5px 5px #d90cb3,-4.8px 15.7px 5.6px #ad2a95,-43.1px 12.7px 6.2px #823877,-50.7px 8.9px 5.6px #563650,-47.5px 7.8px 7.7px #2b2329;}
 12.5%{text-shadow:-26.6px 13px 5px #d90cb3,-14.4px 12.8px 5px #ad2a95,-51.3px 9.9px 5px #823877,-46.5px 9.9px 6.6px #563650,-37.6px 9.7px 9.1px #2b2329;}
 25%{text-shadow:-18.4px 15.4px 5px #d90cb3,-16.9px 12.1px 5px #ad2a95,-46.2px 11.6px 5.6px #823877,-38.2px 11.9px 8.7px #563650,-31.3px 10.9px 9.9px #2b2329;}
 37.5%{text-shadow:-12.9px 17.1px 5px #d90cb3,-4.5px 15.8px 5.7px #ad2a95,-38.8px 14.2px 7px #823877,-40.3px 11.4px 8.1px #563650,-35.2px 10.2px 9.4px #2b2329;}
 50%{text-shadow:-20.9px 14.7px 5px #d90cb3,-15.8px 12.4px 5px #ad2a95,-45px 12.1px 5.8px #823877,-49.2px 9.3px 6px #563650,-45.3px 8.2px 8px #2b2329;}
 62.5%{text-shadow:-26.7px 13px 5px #d90cb3,-15.6px 12.5px 5px #ad2a95,-51.5px 9.8px 5px #823877,-49.3px 9.2px 6px #563650,-50.8px 7.2px 7.3px #2b2329;}
 75%{text-shadow:-18.9px 15.3px 5px #d90cb3,-4.5px 15.8px 5.6px #ad2a95,-44.3px 12.3px 5.9px #823877,-40.5px 11.3px 8.1px #563650,-45.8px 8.1px 8px #2b2329;}
 87.5%{text-shadow:-12.8px 17.1px 5px #d90cb3,-17.1px 12px 5px #ad2a95,-38.9px 14.2px 6.9px #823877,-38.1px 11.9px 8.7px #563650,-35.7px 10.1px 9.3px #2b2329;}
 100%{text-shadow:-20.4px 14.8px 5px #d90cb3,-14.2px 12.9px 5px #ad2a95,-46.9px 11.4px 5.5px #823877,-46.3px 9.9px 6.7px #563650,-31.2px 10.9px 9.9px #2b2329;}
}
@-webkit-keyframes blaze { 0%{text-shadow:-21.5px 14.5px 5px #d90cb3,-4.8px 15.7px 5.6px #ad2a95,-43.1px 12.7px 6.2px #823877,-50.7px 8.9px 5.6px #563650,-47.5px 7.8px 7.7px #2b2329;}
 12.5%{text-shadow:-26.6px 13px 5px #d90cb3,-14.4px 12.8px 5px #ad2a95,-51.3px 9.9px 5px #823877,-46.5px 9.9px 6.6px #563650,-37.6px 9.7px 9.1px #2b2329;}
 25%{text-shadow:-18.4px 15.4px 5px #d90cb3,-16.9px 12.1px 5px #ad2a95,-46.2px 11.6px 5.6px #823877,-38.2px 11.9px 8.7px #563650,-31.3px 10.9px 9.9px #2b2329;}
 37.5%{text-shadow:-12.9px 17.1px 5px #d90cb3,-4.5px 15.8px 5.7px #ad2a95,-38.8px 14.2px 7px #823877,-40.3px 11.4px 8.1px #563650,-35.2px 10.2px 9.4px #2b2329;}
 50%{text-shadow:-20.9px 14.7px 5px #d90cb3,-15.8px 12.4px 5px #ad2a95,-45px 12.1px 5.8px #823877,-49.2px 9.3px 6px #563650,-45.3px 8.2px 8px #2b2329;}
 62.5%{text-shadow:-26.7px 13px 5px #d90cb3,-15.6px 12.5px 5px #ad2a95,-51.5px 9.8px 5px #823877,-49.3px 9.2px 6px #563650,-50.8px 7.2px 7.3px #2b2329;}
 75%{text-shadow:-18.9px 15.3px 5px #d90cb3,-4.5px 15.8px 5.6px #ad2a95,-44.3px 12.3px 5.9px #823877,-40.5px 11.3px 8.1px #563650,-45.8px 8.1px 8px #2b2329;}
 87.5%{text-shadow:-12.8px 17.1px 5px #d90cb3,-17.1px 12px 5px #ad2a95,-38.9px 14.2px 6.9px #823877,-38.1px 11.9px 8.7px #563650,-35.7px 10.1px 9.3px #2b2329;}
 100%{text-shadow:-20.4px 14.8px 5px #d90cb3,-14.2px 12.9px 5px #ad2a95,-46.9px 11.4px 5.5px #823877,-46.3px 9.9px 6.7px #563650,-31.2px 10.9px 9.9px #2b2329;}
}
@-moz-keyframes blaze { 0%{text-shadow:-21.5px 14.5px 5px #d90cb3,-4.8px 15.7px 5.6px #ad2a95,-43.1px 12.7px 6.2px #823877,-50.7px 8.9px 5.6px #563650,-47.5px 7.8px 7.7px #2b2329;}
 12.5%{text-shadow:-26.6px 13px 5px #d90cb3,-14.4px 12.8px 5px #ad2a95,-51.3px 9.9px 5px #823877,-46.5px 9.9px 6.6px #563650,-37.6px 9.7px 9.1px #2b2329;}
 25%{text-shadow:-18.4px 15.4px 5px #d90cb3,-16.9px 12.1px 5px #ad2a95,-46.2px 11.6px 5.6px #823877,-38.2px 11.9px 8.7px #563650,-31.3px 10.9px 9.9px #2b2329;}
 37.5%{text-shadow:-12.9px 17.1px 5px #d90cb3,-4.5px 15.8px 5.7px #ad2a95,-38.8px 14.2px 7px #823877,-40.3px 11.4px 8.1px #563650,-35.2px 10.2px 9.4px #2b2329;}
 50%{text-shadow:-20.9px 14.7px 5px #d90cb3,-15.8px 12.4px 5px #ad2a95,-45px 12.1px 5.8px #823877,-49.2px 9.3px 6px #563650,-45.3px 8.2px 8px #2b2329;}
 62.5%{text-shadow:-26.7px 13px 5px #d90cb3,-15.6px 12.5px 5px #ad2a95,-51.5px 9.8px 5px #823877,-49.3px 9.2px 6px #563650,-50.8px 7.2px 7.3px #2b2329;}
 75%{text-shadow:-18.9px 15.3px 5px #d90cb3,-4.5px 15.8px 5.6px #ad2a95,-44.3px 12.3px 5.9px #823877,-40.5px 11.3px 8.1px #563650,-45.8px 8.1px 8px #2b2329;}
 87.5%{text-shadow:-12.8px 17.1px 5px #d90cb3,-17.1px 12px 5px #ad2a95,-38.9px 14.2px 6.9px #823877,-38.1px 11.9px 8.7px #563650,-35.7px 10.1px 9.3px #2b2329;}
 100%{text-shadow:-20.4px 14.8px 5px #d90cb3,-14.2px 12.9px 5px #ad2a95,-46.9px 11.4px 5.5px #823877,-46.3px 9.9px 6.7px #563650,-31.2px 10.9px 9.9px #2b2329;}
}

```

##### tips

You may notice that the css in pretty heavy. I have to prefix all the properties as there are not yet standards. You can reduce drastically the weight by using less colors and less keyframes.


### The tricks

To achieve this effect, I use some css shadow property and animate them with key frame animation.

The shadow params values oscillate following a random pattern to looks chaotic and make a realistic fire effect.

The `box-shadox` property does not offer a convincing render. We need more asperities on the element to figure the flame.

That's why I use `:before` pseudo class to insert content on top of the element. A chain of characters "xlxlxxxll" do the job pretty well. It's this chain that we animate with `text-shadow` property.


### Author

Me, @Platane.
If you like my work, there is some more over there [arthur-brongniart.fr](http://arthur-brongniart.fr)


