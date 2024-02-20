# MorePlan.it
<!DOCTYPE html>
<!--[if lt IE 7]>      <html class="no-js lt-ie9 lt-ie8 lt-ie7"> <![endif]-->
<!--[if IE 7]>         <html class="no-js lt-ie9 lt-ie8"> <![endif]-->
<!--[if gt IE 8]><!-->
<html lang="{block:English}en{/block:English}{block:German}de{/block:German}{block:French}fr{/block:French}{block:Italian}it{/block:Italian}{block:Japanese}ja{/block:Japanese}{block:Turkish}tr{/block:Turkish}{block:Spanish}es{/block:Spanish}{block:Russian}ru{/block:Russian}{block:Polish}pl{/block:Polish}{block:PortuguesePT}pt-PT{/block:PortuguesePT}{block:PortugueseBR}pt-BR{/block:PortugueseBR}{block:Dutch}nl{/block:Dutch}{block:Korean}ko{/block:Korean}{block:ChineseSimplified}zh-CN{/block:ChineseSimplified}{block:ChineseTraditional}zh-TW{/block:ChineseTraditional}{block:ChineseHK}zh-HK{/block:ChineseHK}{block:Indonesian}id{/block:Indonesian}{block:Hindi}hi{/block:Hindi}" data-force-color-mode="light">
<head>
    <script>
      const colorModeOverride = window.localStorage.getItem('color-mode');
      const hasColorModeOverride = typeof colorModeOverride === 'string';
      if (hasColorModeOverride) {
         document.documentElement.setAttribute('data-force-color-mode', colorModeOverride);
      }
     </script>
     <title>{block:TagPage}{lang:Posts tagged Tag} | {/block:TagPage} {block:SearchPage} {lang:SearchResultCount results for SearchQuery} {block:NoSearchResults}{lang:No results found}{/block:NoSearchResults} | {/block:SearchPage}{block:PostSummary}{PostSummary} &mdash; {/block:PostSummary}{Title}</title>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    {block:Description}
        <meta name="description" content="{MetaDescription}">
    {/block:Description}
    {MobileAppHeaders}
    <link rel="shortcut icon" href="{Favicon}">
    <link rel="apple-touch-icon-precomposed" href="{PortraitURL-128}">
    <link rel="alternate" type="application/rss+xml" href="{RSS}">
    <link rel="stylesheet" href="https://static.tumblr.com/5ojoydj/NO8s1g7kj/style.min.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Be+Vietnam+Pro:ital,wght@0,400;0,600;1,400;1,600&family=Instrument+Sans:ital,wght@0,400;0,600;1,400;1,600&family=Instrument+Serif:ital@0;1&family=Inter:wght@400;600&family=Roboto:ital,wght@0,400;0,500;1,400;1,500&family=Source+Sans+3:ital,wght@0,400;0,600;1,400;1,600&family=Source+Serif+4:ital,wght@0,400;0,600;1,400;1,600&display=swap" rel="stylesheet">

    <link rel="stylesheet" type="text/css" href="https://assets.tumblr.com/fonts/favorit/stylesheet.css?v=1">
    <link rel="stylesheet" href="https://maxst.icons8.com/vue-static/landings/line-awesome/line-awesome/1.3.0/css/line-awesome.min.css">

    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/tiny-slider/2.9.4/tiny-slider.css">
    <!--[if (lt IE 9)]><script src="https://cdnjs.cloudflare.com/ajax/libs/tiny-slider/2.9.4/min/tiny-slider.helper.ie8.js"></script><![endif]-->

    <!-- tabs -->
    <link rel="stylesheet" type="text/css" href="https://cdn.jsdelivr.net/gh/cferdinandi/tabby@12.0.0/dist/css/tabby-ui.min.css">
    <script src="https://cdn.jsdelivr.net/gh/cferdinandi/tabby@12.0.0/dist/js/tabby.polyfills.min.js"></script>
    <link href="https://cdn.jsdelivr.net/gh/boscoxvi/npfphotosets@master/npfphotosetstyle.css" rel="stylesheet">
    
    {block:Hidden}
    <meta name="image:Hero Top Background Image" content=""/>
    <meta name="image:Footer Bottom Background Image" content=""/>
    
    <meta name="color:Accent Color" content="#F3A2BB" />
    <meta name="color:Background Page Color" content="#FFFFFF" />
    <meta name="color:Background Container Color" content="#EEEEEE" />
    <meta name="color:Border Color" content="#dddddd" />
    
    <meta name="color:Header Navigation Background Color" content="#ffffff" />
    <meta name="color:Header Navigation Link Color" content="#111111" />
    <meta name="color:Header Navigation Dots One" content="#F3A2BB" />
    <meta name="color:Header Navigation Dots Two" content="#111111" />
    
    <meta name="color:Posts Background Color" content="#ffffff" />
    <meta name="color:Posts Body Link Color" content="#000000" />
    <meta name="color:Posts Body Heading Color" content="#111111" />
    <meta name="color:Posts Body Text Color" content="#555555" />
    
    <meta name="color:Button Background Color" content="#111111" />
    <meta name="color:Button Background Color On Hover" content="#F3A2BB" />
    <meta name="color:Button Text Color" content="#ffffff" />
    <meta name="color:Button Text Color On Hover" content="#111111" />
    
    <meta name="color:Social Media Button Background Color" content="#111111" />
    <meta name="color:Social Media Button Background Color On Hover" content="#F3A2BB" />
    <meta name="color:Social Media Button Text Color" content="#ffffff" />
    <meta name="color:Social Media Button Text Color On Hover" content="#111111" />
    
    <meta name="color:Hero Top Text Color" content="#111111" />
    <meta name="color:Hero Top Overlay Color" content="#000000" />
    
    <meta name="color:Selection Text Color" content="#111111" />
    <meta name="color:Selection Text Background Color" content="#FFFFE0" />
    
    <meta name="select:Blog Layout" content="normal" title="Normal">
    <meta name="select:Blog Layout" content="masonry" title="Masonry">
    
    <meta name="select:Blog Width" content="100%" title="Default">
    <meta name="select:Blog Width" content="85%" title="Narrower"> 
    
    <meta name="select:Blog Post Masonry Columns" content="is-two-column" title="2 Columns">
    <meta name="select:Blog Post Masonry Columns" content="is-three-column" title="3 Columns">
    
    <meta name="select:Search Form" content="is-displayed" title="Show">
    <meta name="select:Search Form" content="is-hidden" title="Hide">
    <meta name="select:Search Suggestions" content="is-displayed" title="Show">
    <meta name="select:Search Suggestions" content="is-hidden" title="Hide"> 
    
    <meta name="select:Font Heading" content="Instrument Serif, serif" title="Instrument Serif">
    <meta name="select:Font Heading" content="'Source Serif 4', serif;" title="Source Serif">
    <meta name="select:Font Heading" content="Favorit, sans-serif" title="Favorit (Tumblr)">
    <meta name="select:Font Heading" content="Be Vietnam Pro, sans-serif" title="Be Vietnam Pro">
    <meta name="select:Font Heading" content="Inter, sans-serif" title="Inter">
    <meta name="select:Font Heading" content="Roboto, sans-serif" title="Roboto">
    
    <meta name="select:Font Body" content="Favorit, sans-serif" title="Favorit (Tumblr)">
    <meta name="select:Font Body" content="Be Vietnam Pro, sans-serif" title="Be Vietnam Pro">
    <meta name="select:Font Body" content="Inter, sans-serif" title="Inter">
    <meta name="select:Font Body" content="Roboto, sans-serif" title="Roboto">
    <meta name="select:Font Body" content="'Source Sans 3', sans-serif" title="Source Sans Pro">
    <meta name="select:Font Body" content="Instrument Sans, sans-serif" title="Instrument Sans">
     
    <meta name="select:Font Size" content="14" title="14px">
    <meta name="select:Font Size" content="15" title="15px">
    <meta name="select:Font Size" content="16" title="16px">
    
    <meta name="select:Posts Shorten" content="is-shorten-long-post" title="Yes">
    <meta name="select:Posts Shorten" content="is-not-shorten-long-post" title="No">
    
    <meta name="select:Posts Tags" content="is-displayed" title="Show (Default)">
    <meta name="select:Posts Tags" content="is-expand" title="On Click">
    <meta name="select:Posts Tags" content="is-hidden" title="Off">
    
    <meta name="select:Posts Date Format" content="is-date-one" title="Posted on 1 January, 1970">
    <meta name="select:Posts Date Format" content="is-date-two" title="Posted on Thursday, 1 January 1970">
    <meta name="select:Posts Date Format" content="is-date-three" title="Posted on Thursday January 1st">
    <meta name="select:Posts Date Format" content="is-date-four" title="Posted at 10.00 PM">
    <meta name="select:Posts Date Format" content="is-date-five" title="Posted on Tuesday the 1st of January 1970 at 10:00 PM ">
    
    <meta name="select:Header Decoration Type" content="is-circle" title="Two Dots">
    <meta name="select:Header Decoration Type" content="is-avatar" title="Avatar">
    <meta name="select:Header Decoration Type" content="is-none" title="None">
    
    <meta name="select:Header Dark Mode Button" content="is-displayed" title="Show">
    <meta name="select:Header Dark Mode Button" content="is-hidden" title="Hide">
    
    <meta name="select:Hero Overlay Level" content="0.0" title="None (0%)">
    <meta name="select:Hero Overlay Level" content="0.1" title="10%">
    <meta name="select:Hero Overlay Level" content="0.2" title="20%">
    <meta name="select:Hero Overlay Level" content="0.3" title="30%">
    <meta name="select:Hero Overlay Level" content="0.4" title="40%">
    <meta name="select:Hero Overlay Level" content="0.5" title="50%">
    <meta name="select:Hero Overlay Level" content="0.6" title="60%">
    <meta name="select:Hero Overlay Level" content="0.7" title="70%">
    <meta name="select:Hero Overlay Level" content="0.8" title="80%">
    <meta name="select:Hero Overlay Level" content="0.9" title="90%">
    
    <meta name="select:Featured Posts Slideshow Section" content="is-hidden" title="Hidden">
    <meta name="select:Featured Posts Slideshow Section" content="is-displayed" title="Show">
    
    <meta name="select:Back To Top Button" content="is-displayed" title="On">
    <meta name="select:Back To Top Button" content="is-hidden" title="Off">
    
    <meta name="select:Footer Visibility" content="is-displayed" title="On">
    <meta name="select:Footer Visibility" content="is-hidden" title="Off">
    <meta name="select:Footer Navigation Visibility" content="is-displayed" title="On">
    <meta name="select:Footer Navigation Visibility" content="is-displayed" title="On">
    
    <meta name="text:Hero Top Section Height" content="465px"/>
    <meta name="text:Footer Section Height" content="350px"/>
    
    <meta name="text:Hero Top Button Link" content="https://"/>
    <meta name="text:Hero Top Button Text Label" content="Button link here"/>
    <meta name="text:Featured Section Heading Text" content="Featured Section"/>
    <meta name="text:Featured Section Description Text" content="Hey, this is an example test for the body text of the featured section. You can add the text as many much as possible (or just simply delete this if you don't want. Thank you."/>
     <meta name="text:Search Suggestions Heading" content="Suggestions for you ✨"/>
    
    <meta name='text:Disqus Shortname' content=""/>
    
    <meta name="text:Facebook URL" content=""/>
    <meta name="text:Twitter URL" content=""/>
    <meta name="text:Patreon URL" content=""/>
    <meta name="text:Twitch URL" content=""/>
    <meta name="text:Youtube URL" content=""/>
    <meta name="text:Instagram URL" content=""/>
    <meta name="text:Discord URL" content=""/>
    <meta name="text:Kofi URL" content=""/>
    <meta name="text:Tiktok URL" content=""/>
    <meta name="text:Mastodon URL" content=""/>
    
    <meta name="if:Selection Color" content="1"/>
    <meta name="if:Custom Scrollbar" content="1"/>
    {/block:Hidden}
    <style id="main">
        :root {
            --title-font: {TitleFont};
            --title-font-weight: {TitleFontWeight};

            --heading-font:{select:Font Heading};
            --body-font:{select:Font Body};
            --code-font: 'Consolas', monospace;

            --accent:{RGBcolor:Accent Color};

            --bg-img: url('https://assets.tumblr.com/images/x.gif?v=1');

            --btn-primary:{RGBcolor:Button Background Color};
            --btn-text-primary:{RGBcolor:Button Text Color};

            --btn-primary-hover:{RGBcolor:Button Background Color On Hover};
            --btn-text-primary-hover:{RGBcolor:Button Text Color On Hover};

            --bg-card-pinned-border:210, 153, 159;

            --pinned-label-bg:210, 153, 159;
            --pinned-label-text:255,255,255;

            --hero-bg-img:url('{image:Hero Top Background Image}');

            --footer-bg-img:url('{image:Footer Bottom Background Image}');
            --footer-height:{text:Footer Section Height};

            --social-media-btn:{RGBcolor:Social Media Button Background Color};
            --social-media-btn-text:{RGBcolor:Social Media Button Text Color};
            --social-media-btn-hover:{RGBcolor:Social Media Button Background Color On Hover};
            --social-media-btn-text-hover:{RGBcolor:Social Media Button Text Color On Hover};

            --header-navigation-circle-one:{RGBcolor:Header Navigation Dots One};
            
            --hero-overlay:{RGBcolor:Hero Top Overlay Color};
            --hero-overlay-level:{select:Hero Overlay Level};
            --hero-height:{text:Hero Top Section Height};

            --text-xxl: clamp(2rem, (1rem + 2.5vw), 3rem);
            --text-xl: clamp(1.25rem, (1rem + 2.5vw), 2rem);
            --text-lg: clamp(1rem, (1rem + 2.5vw), 1.125rem);
            --text-md: clamp(0.85rem, (1rem + 2.5vw) 1rem);
            --text-sm: clamp(0.65rem, (1rem + 2.5vw), 0.85rem);

            --padding-lg: clamp(2rem, 2.5vw, 2.25rem);
            --padding-md: clamp(1.45rem, 2.5vw, 2rem);
            --padding-sm: clamp(1rem, 2.5vw, 1.5rem);

            --blog-width:{select:Blog Width};

            --font-size:14px;
             font-size:var(--font-size);
        }

        :root[data-force-color-mode="light"] {
            --bg-color: {RGBcolor:Background Page Color};
            --bg-post-color:{RGBcolor:Background Container Color};

            --bg-card:{RGBcolor:Posts Background Color};
            --body-text: {RGBcolor:Posts Body Text Color};
            --body-link: {RGBcolor:Posts Body Link Color};
            --heading-text: {RGBcolor:Posts Body Heading Color};

            --bg-card-pinned:var(--bg-card);

            --post-bubble-bg:238,238,238;
            --post-bubble-text:17,17,17;

            --hero-color:{RGBcolor:Hero Top Text Color};

            --border-color:{RGBcolor:Border Color};

            --header-navigation-bg:{RGBcolor:Header Navigation Background Color};
            --header-navigation-text:{RGBcolor:Header Navigation Link Color};

            --header-navigation-circle-two:{RGBcolor:Header Navigation Dots Two};

            --tags-button-text:153, 153, 153;
            --tags-button-text-hover:{RGBcolor:Posts Body Link Color};

            --action-button-text:{RGBcolor:Posts Body Link Color};
            --action-button-border:{RGBcolor:Border Color};
            --action-button-bg-hover:'';
            --action-button-text-hover{RGBcolor:Posts Body Link Color};
        }

        :root[data-force-color-mode="dark"] {
            --bg-color:27, 33, 40;
            --bg-post-color:33, 41, 49;

            --bg-card: 45, 56, 67;
            --body-text:199, 204, 209;
            --body-link: 255,255,255;
            --heading-text: 255,255,255;

            --bg-card-pinned:var(--bg-card);

            --post-bubble-bg:33, 41, 49;
            --post-bubble-text:199, 204, 209;

            --hero-color: 255,255,255;

            --border-color:65, 72, 78;
            
            --header-navigation-circle-two:199, 204, 209;

            --header-navigation-bg:27, 33, 40;
            --header-navigation-text:255,255,255;
   
            --tags-button-text:199, 204, 209;
            --tags-button-text-hover:255,255,255;

            --action-button-text:199, 204, 209;
            --action-button-border:199, 204, 209;
            --action-button-bg-hover:248, 232, 233;
            --action-button-text-hover:255,255,255;
        }
        
        /* tumblr controls */
        body > .tmblr-iframe.tmblr-iframe--unified-controls {
          position: absolute !important;
          right: calc(50% - 1300px/2 + 50px) !important;
          left: auto;
          top: 90px;
          transform: scale(0.85);
          transform-origin: top right;
          z-index:99!important;
        }
        body.is-pushed > .tmblr-iframe.tmblr-iframe--unified-controls {
            top: 175px;
        }
        
        {block:IndexPage}
        body.is-three-column[data-blog-style="masonry"] > .tmblr-iframe.tmblr-iframe--unified-controls {   
            right:calc(50% - 1380px/2 + 50px) !important;
        }
        {/block:IndexPage}
        
        @media (max-width:991.98px) {
            body > .tmblr-iframe.tmblr-iframe--unified-controls {
                display:none!important;
            }
        }
        
        /* others */
        {block:IfSelectionColor}
        ::selection {
            background:{color:Selection Text Background Color};
            color:{color:Selection Text Color};
        }
             
        ::-moz-selection {
            background:{color:Selection Text Background Color};
            color:{color:Selection Text Color};
        }
             
        ::-webkit-selection {
            background:{color:Selection Text Background Color};
            color:{color:Selection Text Color};
        }
        {/block:IfSelectionColor}
        
        .posts__dated__perma a[data-article-date="enabled"] 
        > span.d-display__{select:Posts Date Format} {
            display:block!important;
        }
        
        @media (min-width:992px) {
            .wrapper__featured {
                padding-left: calc(100% - var(--blog-width) - 90px);
            } 
        }
    </style>
    <style id="custom">
         {CustomCSS} 
    </style>
</head>
<body data-page-type="{block:IndexPage}index{/block:IndexPage}{block:PermalinkPage}permalink{/block:PermalinkPage}{block:TagPage}tag{/block:TagPage}{block:DayPage}day{/block:DayPage}{block:SearchPage}search{/block:SearchPage}" data-blog-style="{block:IndexPage}{select:Blog Layout}{/block:IndexPage}{block:PermalinkPage}normal{/block:PermalinkPage}" class="is-featured {select:Posts Shorten} {select:Blog Post Masonry Columns} {block:IfCustomScrollbar}is-scrollbar{/block:IfCustomScrollbar}">
    
    <nav class="nav">
        <div class="nav__inner | container--width-xl margin--x-auto">
            <div class="nav__logo {select:Header Decoration Type}">
                <div class="nav__logo__circle nav__logo__circle-one" aria-hidden="true"></div>
                <div class="nav__logo__circle nav__logo__circle-two" aria-hidden="true"></div>
                <a id="avatar" class="avatar-{AvatarShape}" href="/"><img src="{PortraitURL-128}" alt="{Name}"/></a>
            </div>
            <div class="nav__links | flex flex--align-center">
                <ul class="nav__menu">
                    <li class="nav__menu__item {block:HomePage}nav__menu__item-active{/block:HomePage}"><a href="/">{lang:Home}</a></li>
                    <li class="nav__menu__item"><a href="/archive">{lang:Archive}</a></li>
                    {block:AskEnabled}<li class="nav__menu__item {block:AskPage}nav__menu__item-active{/block:AskPage}"><a href="/ask">{AskLabel}</a></li>{/block:AskEnabled}
                    {block:SubmissionsEnabled}
                    <li class="nav__menu__item {block:SubmitPage}nav__menu__item-active{/block:SubmitPage}"><a href="/submit">{SubmitLabel}</a></li>{/block:SubmissionsEnabled}
                </ul>
                <div class="nav__search {select:Search Form}">
                  <form action="/search" method="get" class="nav__search__form" autocomplete="off">
                     <input type="text" id="search" name="q" value="{SearchQuery}" placeholder="{lang:Search keywords}...">
                     <button type="submit">
                         <span>
                            <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><circle cx="11" cy="11" r="8"></circle><line x1="21" y1="21" x2="16.65" y2="16.65"></line></svg>
                         </span>
                     </button>
                  </form>
                  {block:HasFeaturedTags}
                  <div class="nav__search__suggestion {select:Search Suggestions}">
                      {block:IfSearchSuggestionsHeading}<h2>{text:Search Suggestions Heading}</h2>{/block:IfSearchSuggestionsHeading}
                      <ul class="featured-tags">
                            {block:FeaturedTags}
                                <li>
                                    <a href="{TagURL}">{Tag}</a>
                                </li>
                            {/block:FeaturedTags}
                        </ul>
                  </div>
                  {/block:HasFeaturedTags}
                </div>
                <div class="nav__button">
                    {block:HasPages} 
                    <button class="btn-nav" aria-label="Navigation"><svg xmlns="http://www.w3.org/2000/svg"
                            width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor"
                            stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                            <circle cx="12" cy="12" r="1"></circle>
                            <circle cx="19" cy="12" r="1"></circle>
                            <circle cx="5" cy="12" r="1"></circle>
                        </svg></button>
                    {/block:HasPages} 
                    <button class="btn-dark {select:Header Dark Mode Button}" aria-label="Switch mode"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><circle cx="12" cy="12" r="5"/><path d="M12 1v2M12 21v2M4.2 4.2l1.4 1.4M18.4 18.4l1.4 1.4M1 12h2M21 12h2M4.2 19.8l1.4-1.4M18.4 5.6l1.4-1.4"/></svg></button>
                </div>
            </div>
        </div>
        {block:HasPages} 
        <div class="nav__additional | container--width-xl margin--x-auto">
            <ul class="nav__additional__links">
               {block:Pages}<li><a href="{URL}">{Label}</a></li>{/block:Pages}
            </ul>
        </div>
        {/block:HasPages} 
    </nav>
  
    <main class="wrapper | container--width-xl margin--x-auto">
        <header class="wrapper__hero" style="background-image: var(--hero-bg-img);">
            <div class="wrapper__hero__overlay"></div>
            <div class="wrapper__hero__inner">
                <div class="wrapper__hero__avatar">
                  {block:ShowAvatar}
                  <a id="avatar" class="avatar-{AvatarShape}" href="/"><img src="{PortraitURL-128}" alt="{Name}"/></a>
                  {/block:ShowAvatar}
                </div>
                {block:ShowTitle}<h1>{Title}</h1>{/block:ShowTitle}
                {block:ShowDescription}<p>{Description}</p>{/block:ShowDescription}
                <div class="btn__wrapper | margin--top-30" data-wrapper-type="row">
                    {block:IfHeroTopButtonTextLabel}
                    <a href="{text:Hero Top Button Link}" class="btn btn__primary">{text:Hero Top Button Text Label}</a>
                    {/block:IfHeroTopButtonTextLabel}
                    <ul class="wrapper__hero__socmed">
                        {block:IfFacebookURL}
                        <li><a href="{text:Facebook URL}" title="Facebook">
                           <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="currentColor"><path d="M20 0a4 4 0 0 1 4 4v16a4 4 0 0 1-4 4H4a4 4 0 0 1-4-4V4a4 4 0 0 1 4-4h16zm-4 7.28V4.5h-2.29c-2.1 0-3.42 1.6-3.42 3.89v1.67H8v2.77h2.29v6.67h2.85v-6.67h2.29l.57-2.77h-2.86V8.94c0-1.1.58-1.66 1.72-1.66H16z"/></svg>
                        </a></li>
                        {/block:IfFacebookURL}
                        {block:IfTwitterURL}
                        <li><a href="{text:Twitter URL}" title="Twitter">
                              <svg role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24">
                                 <title>Twitter icon</title>
                                 <path
                                    d="M23.953 4.57a10 10 0 01-2.825.775 4.958 4.958 0 002.163-2.723c-.951.555-2.005.959-3.127 1.184a4.92 4.92 0 00-8.384 4.482C7.69 8.095 4.067 6.13 1.64 3.162a4.822 4.822 0 00-.666 2.475c0 1.71.87 3.213 2.188 4.096a4.904 4.904 0 01-2.228-.616v.06a4.923 4.923 0 003.946 4.827 4.996 4.996 0 01-2.212.085 4.936 4.936 0 004.604 3.417 9.867 9.867 0 01-6.102 2.105c-.39 0-.779-.023-1.17-.067a13.995 13.995 0 007.557 2.209c9.053 0 13.998-7.496 13.998-13.985 0-.21 0-.42-.015-.63A9.935 9.935 0 0024 4.59z" />
                              </svg></a></li>
                        {/block:IfTwitterURL}
                        {block:IfPatreonURL}
                        <li><a href="{text:Patreon URL}" title="Patreon">
                              <svg role="img" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                                 <title>Patreon icon</title>
                                 <path
                                    d="M0 .48v23.04h4.22V.48zm15.385 0c-4.764 0-8.641 3.88-8.641 8.65 0 4.755 3.877 8.623 8.641 8.623 4.75 0 8.615-3.868 8.615-8.623C24 4.36 20.136.48 15.385.48z" />
                              </svg></a></li>
                        {/block:IfPatreonURL}
                        {block:IfTwitchURL}
                        <li><a href="{text:Twitch URL}" title="Twitch">
                              <svg role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24">
                                 <title>Twitch icon</title>
                                 <path
                                    d="M11.571 4.714h1.715v5.143H11.57zm4.715 0H18v5.143h-1.714zM6 0L1.714 4.286v15.428h5.143V24l4.286-4.286h3.428L22.286 12V0zm14.571 11.143l-3.428 3.428h-3.429l-3 3v-3H6.857V1.714h13.714Z" />
                              </svg>
                           </a></li>
                        {/block:IfTwitchURL}
                        {block:IfKofiURL}
                        <li>
                            <a href="{text:Kofi URL}" title="Ko-fi">
                                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24">
  <path d="M23.881 8.948c-.773-4.085-4.859-4.593-4.859-4.593H.723c-.604 0-.679.798-.679.798s-.082 7.324-.022 11.822c.164 2.424 2.586 2.672 2.586 2.672s8.267-.023 11.966-.049c2.438-.426 2.683-2.566 2.658-3.734 4.352.24 7.422-2.831 6.649-6.916zm-11.062 3.511c-1.246 1.453-4.011 3.976-4.011 3.976s-.121.119-.31.023c-.076-.057-.108-.09-.108-.09-.443-.441-3.368-3.049-4.034-3.954-.709-.965-1.041-2.7-.091-3.71.951-1.01 3.005-1.086 4.363.407 0 0 1.565-1.782 3.468-.963 1.904.82 1.832 3.011.723 4.311zm6.173.478c-.928.116-1.682.028-1.682.028V7.284h1.77s1.971.551 1.971 2.638c0 1.913-.985 2.667-2.059 3.015z"/>
</svg>
                            </a>
                        </li>
                        {/block:IfKofiURL}
                        {block:IfYoutubeURL}
                        <li><a href="{text:YouTube URL}" title="YouTube">
                              <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="currentColor">
                                 <path
                                    d="M12.04 3.5c.59 0 7.54.02 9.34.5a3.02 3.02 0 0 1 2.12 2.15C24 8.05 24 12 24 12v.04c0 .43-.03 4.03-.5 5.8A3.02 3.02 0 0 1 21.38 20c-1.76.48-8.45.5-9.3.51h-.17c-.85 0-7.54-.03-9.29-.5A3.02 3.02 0 0 1 .5 17.84c-.42-1.61-.49-4.7-.5-5.6v-.5c.01-.9.08-3.99.5-5.6a3.02 3.02 0 0 1 2.12-2.14c1.8-.49 8.75-.51 9.34-.51zM9.54 8.4v7.18L15.82 12 9.54 8.41z" />
                              </svg>
                           </a></li>
                        {/block:IfYoutubeURL}
                        
                        {block:IfInstagramURL}
                        <li><a href="{text:Instagram URL}" title="Instagram">
                              <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="currentColor">
                                 <path
                                    d="M16.98 0a6.9 6.9 0 0 1 5.08 1.98A6.94 6.94 0 0 1 24 7.02v9.96c0 2.08-.68 3.87-1.98 5.13A7.14 7.14 0 0 1 16.94 24H7.06a7.06 7.06 0 0 1-5.03-1.89A6.96 6.96 0 0 1 0 16.94V7.02C0 2.8 2.8 0 7.02 0h9.96zm.05 2.23H7.06c-1.45 0-2.7.43-3.53 1.25a4.82 4.82 0 0 0-1.3 3.54v9.92c0 1.5.43 2.7 1.3 3.58a5 5 0 0 0 3.53 1.25h9.88a5 5 0 0 0 3.53-1.25 4.73 4.73 0 0 0 1.4-3.54V7.02a5 5 0 0 0-1.3-3.49 4.82 4.82 0 0 0-3.54-1.3zM12 5.76c3.39 0 6.2 2.8 6.2 6.2a6.2 6.2 0 0 1-12.4 0 6.2 6.2 0 0 1 6.2-6.2zm0 2.22a3.99 3.99 0 0 0-3.97 3.97A3.99 3.99 0 0 0 12 15.92a3.99 3.99 0 0 0 3.97-3.97A3.99 3.99 0 0 0 12 7.98zm6.44-3.77a1.4 1.4 0 1 1 0 2.8 1.4 1.4 0 0 1 0-2.8z" />
                              </svg>
                           </a></li>
                        {/block:IfInstagramURL}
                         
                        {block:IfDiscordURL}
                        <li><a href="{text:Discord URL}" title="Discord">
                            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 32 32">
                              <path d="M20.992 20.163a2.884 2.884 0 0 1-2.695-3.03v.007a2.867 2.867 0 0 1 2.687-3.023h.008a2.852 2.852 0 0 1 2.695 3.031v-.008a2.859 2.859 0 0 1-2.688 3.022h-.008zm-9.966 0a2.884 2.884 0 0 1-2.695-3.03v.007a2.867 2.867 0 0 1 2.687-3.023h.008a2.852 2.852 0 0 1 2.695 3.031v-.008a2.867 2.867 0 0 1-2.687 3.023h-.008zM26.393 6.465c-1.763-.832-3.811-1.49-5.955-1.871l-.149-.022a.093.093 0 0 0-.098.045c-.234.411-.488.924-.717 1.45l-.043.111a23.042 23.042 0 0 0-6.985.016l.129-.017c-.27-.63-.528-1.142-.813-1.638l.041.077a.095.095 0 0 0-.083-.047l-.016.001h.001a24.594 24.594 0 0 0-6.256 1.957l.151-.064a.084.084 0 0 0-.04.034C2.706 10.538.998 15.566.998 20.993c0 .907.048 1.802.141 2.684l-.009-.11a.103.103 0 0 0 .039.07 24.623 24.623 0 0 0 7.313 3.738l.176.048a.082.082 0 0 0 .028.004c.032 0 .06-.015.077-.038a17.453 17.453 0 0 0 1.485-2.392l.047-.1a.096.096 0 0 0-.052-.132h-.001a16.266 16.266 0 0 1-2.417-1.157l.077.042a.096.096 0 0 1-.048-.083c0-.031.015-.059.038-.076.157-.118.315-.24.465-.364a.094.094 0 0 1 .097-.013h-.001c2.208 1.061 4.8 1.681 7.536 1.681s5.329-.62 7.643-1.727l-.107.046a.094.094 0 0 1 .099.012c.15.124.307.248.466.365a.098.098 0 0 1 .038.077.097.097 0 0 1-.046.082c-.661.395-1.432.769-2.235 1.078l-.105.036a.097.097 0 0 0-.062.089c0 .016.004.031.011.044v-.001c.501.96 1.009 1.775 1.571 2.548l-.04-.057a.096.096 0 0 0 .106.036h-.001c2.865-.892 5.358-2.182 7.566-3.832l-.065.047a.097.097 0 0 0 .039-.069c.087-.784.136-1.694.136-2.615 0-5.415-1.712-10.43-4.623-14.534l.052.078a.078.078 0 0 0-.038-.036z"/>
                            </svg>

                           </a></li>
                         {/block:IfDiscordURL}
                         
                         {block:IfTiktokURL}   
                         <li><a href="{text:Tiktok URL}" title="Tiktok">
                              <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="currentColor"><path d="M22.5 9.84202C20.4357 9.84696 18.4221 9.20321 16.7435 8.00171V16.3813C16.7429 17.9333 16.2685 19.4482 15.3838 20.7233C14.499 21.9984 13.246 22.973 11.7923 23.5168C10.3387 24.0606 8.75362 24.1477 7.24914 23.7664C5.74466 23.3851 4.39245 22.5536 3.37333 21.383C2.3542 20.2125 1.71674 18.7587 1.54617 17.2161C1.3756 15.6735 1.68007 14.1156 2.41884 12.7507C3.15762 11.3858 4.2955 10.279 5.68034 9.57823C7.06517 8.87746 8.63095 8.61616 10.1683 8.82927V13.0439C9.4648 12.8227 8.70938 12.8293 8.0099 13.063C7.31041 13.2966 6.70265 13.7453 6.2734 14.345C5.84415 14.9446 5.61536 15.6646 5.6197 16.402C5.62404 17.1395 5.8613 17.8567 6.29759 18.4512C6.73387 19.0458 7.34688 19.4873 8.04906 19.7127C8.75125 19.9381 9.5067 19.9359 10.2075 19.7063C10.9084 19.4768 11.5188 19.0316 11.9515 18.4345C12.3843 17.8374 12.6173 17.1188 12.6173 16.3813V0H16.7435C16.7406 0.348435 16.7698 0.696395 16.8307 1.03948V1.03948C16.9741 1.80537 17.2722 2.53396 17.7068 3.18068C18.1415 3.8274 18.7035 4.37867 19.3585 4.80075C20.2903 5.41688 21.3829 5.74528 22.5 5.74505V9.84202Z"/></svg>
                           </a></li>
                         {/block:IfTiktokURL}   
                         {block:IfMastodonURL}   
                         <li><a href="{text:Mastodon URL}" title="Mastodon">
                              <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24">
  <path fill="currentColor" d="M8 7v5a1 1 0 1 1-2 0V7c.005-1.879 1.76-3 3.5-3 1.13 0 1.944.34 2.5.835.556-.494 1.37-.835 2.5-.835 1.739 0 3.494 1.12 3.5 2.999V12a1 1 0 1 1-2 0V6.999C15.94 6.24 15.16 6 14.5 6c-.649 0-1.433.247-1.5.999V10a1 1 0 1 1-2 0V7c-.06-.76-.847-1-1.5-1-.648 0-1.433.248-1.5 1Z"/>
  <path fill="currentColor" fill-rule="evenodd" d="M16 1H8C4.073 1 1.086 4.024 1 7.99V13c0 5.115 3.558 10 9 10h5.48A2.52 2.52 0 0 0 18 20.48c0-1.367-1.134-2.446-2.5-2.48a29.92 29.92 0 0 0-.985 0c-2.079.022-5.247.055-6.232-1.704C12.808 17.126 23 18.5 23 11V8c-.093-3.965-3.066-7-7-7ZM3 13V7.99C3.116 5.113 5.139 3 8 3h8c2.867 0 4.878 2.126 5 5v3c0 6-10.656 3.805-13.757 3.03A1.01 1.01 0 0 0 6 15c0 1.084.275 2.011.86 2.755 1.675 2.136 5.036 2.169 7.658 2.194.34.003.668.007.977.014a.517.517 0 0 1 .505.517.52.52 0 0 1-.52.52H10c-4.346 0-7-3.984-7-8Z" clip-rule="evenodd"/>
</svg>
                           </a></li>
                         {/block:IfMastodonURL}   
                    </ul>
                </div>
            </div>
        </header>
        <div class="wrapper__inner">
            {block:IndexPage}
            <section class="wrapper__featured {select:Featured Posts Slideshow Section}">
                <div class="wrapper__featured__content">
                    <h2>{text:Featured Section Heading Text}</h2>
                    <p>{text:Featured Section Description Text}</p>
                    <ul class="wrapper__featured__controls | margin--top-30" id="customize-controls">
                        <li>
                            <button class="prev">
                                <svg xmlns="http://www.w3.org/2000/svg" width="30" height="30" viewBox="0 0 24 24"
                                    fill="none" stroke="currentColor" stroke-width="1.5" stroke-linecap="round"
                                    stroke-linejoin="round">
                                    <path d="M19 12H6M12 5l-7 7 7 7" />
                                </svg>
                            </button>
                        </li>
                        <li>
                            <button class="next"><svg xmlns="http://www.w3.org/2000/svg" width="30" height="30"
                                    viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width=1.5
                                    stroke-linecap="round" stroke-linejoin="round">
                                    <path d="M5 12h13M12 5l7 7-7 7" />
                                </svg></button>
                        </li>
                    </ul>
                </div>
                <div class="wrapper__featured__slideshow">
                    <div class="slideshow slideshow-all"
                        data-items="1"
                        data-items-md="1"
                        data-items-sm="1"
                        data-loop="false"
                        data-arrow="true"
                        data-autoplay="false"
                        data-speed="500"
                        data-dots="false"
                        data-controls-container="#customize-controls"
                        data-autoplaytime="1000"></div>
                </div>
            </section>
            {/block:IndexPage}
            
            <section class="wrapper__content | container--width-xl margin--x-auto">
               <div class="wrapper__blog" id="blog">
               {block:NoPosts}
                <article class="posts posts-empty posts-text">
                     <div class="posts__inner">
                         <section class="posts__body">
                            <h1>{lang:This Tumblr hasnt made any posts}</h1>
                            <p>{lang:Meditate for a while on this empty Tumblr}</p>
                          </section>
                    </div>
                </article>
                {/block:NoPosts}
               
               {block:TagPage}
                <article class="posts posts-others posts-text">
                     <div class="posts__inner">
                         <section class="posts__body">
                            <h1>Tagged posts</h1>
                            <p>{lang:Showing TagResultCount posts tagged Tag 2}</p>
                          </section>
                    </div>
                </article>
                {/block:TagPage}
                {block:SearchPage}
                <article class="posts posts-others posts-text">
                     <div class="posts__inner">
                         <section class="posts__body">
                            <h1>Searched posts</h1>
                            <p>{lang:Found SearchResultCount results for SearchQuery 2} {block:NoSearchResults}{lang:No search results for SearchQuery 2}{/block:NoSearchResults}</p>
                            <p> </p>
                          </section>
                    </div>
                </article>
                {/block:SearchPage}
                
                <div class="grid-sizer"></div>
                
                {block:Posts inlineMediaWidth="1280" inlineNestedMediaWidth="1280"}            
                <article class="posts posts-{PostType} {block:PinnedPostLabel}{block:IndexPage} pinned{/block:IndexPage}{/block:PinnedPostLabel} {TagsAsClasses}{block:PermalinkPage} is-permalink{/block:PermalinkPage}" data-article-permalink="{Permalink}" data-article-id="{PostID}" data-article-npf="{JSNPF}">
                    {block:Date}
                        {block:PinnedPostLabel}
                        <div class="posts__dated__pinned">
                            <svg fill="currentColor" viewBox="18 13 12 21">
                                <path fill-rule="evenodd" d="M26.252 27.266l-2.078 7.592c-.052.19-.296.19-.348 0l-2.078-7.592h4.504zM29.512 14c.268 0 .488.241.488.536v1.746a.554.554 0 01-.255.47l-1.698 1.193v4.009l1.787 1.257-.034.006c.128.107.2.264.199.43v1.744c0 .296-.22.537-.488.537H18.488c-.268 0-.488-.241-.488-.537v-1.743a.555.555 0 01.255-.47l1.698-1.195v-4.008l-1.787-1.258.034-.006a.554.554 0 01-.199-.43v-1.745c0-.295.22-.536.488-.536h11.023z"></path>
                            </svg>
                           {PinnedPostLabel}
                        </div>
                        {/block:PinnedPostLabel}
                   {/block:Date}
                   
                   {block:Date}
                         <div class="posts__dated">
                           <div class="posts__dated__perma"> 
                              <a href="{Permalink}" data-article-date="enabled">
                                <span class="d-none d-display__is-date-one">{lang:Posted on DayOfMonth Month Year}</span>
                                <span class="d-none d-display__is-date-two">{lang:Posted on DayOfWeek DayOfMonth Month Year}</span>
                                <span class="d-none d-display__is-date-three">{lang:Posted on DayOfWeek Month DayOfMonthWithSuffix}</span>
                                <span class="d-none d-display__is-date-four">{lang:Posted at FormattedTime 2}</span>
                                <span class="d-none d-display__is-date-five">{lang:Posted on DayOfWeek the DayOfMonthWithSuffix of Month Year at FormattedTime}</span>
                              </a>
                            </div>
                            <div class="posts__dated__action">
                               <a href="{Permalink}" class="flex flex--align-center"><span class="is-notes">{NoteCountWithLabel}</span> <svg class="margin--left-10" xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><g fill="none" fill-rule="evenodd"><path d="M18 14v5a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2V8c0-1.1.9-2 2-2h5M15 3h6v6M10 14L20.2 3.8"/></g></svg></a>
                            </div>
                        </div>
                   {/block:Date}
                
                 <section class="posts__media">
                       {block:Text}{block:Title}<h1><a href="{Permalink}">{Title}</a></h1>{/block:Title}{/block:Text}
                       {block:Photo}
                          <figure class="photo">
                            {LinkOpenTag}
                                   <img src="{PhotoURL-HighRes}" alt="{PhotoAlt}">
                            {LinkCloseTag}
                         </figure>
                      {/block:Photo}
                                                
                      {block:Photoset}
                       <div class="npf_photoset" data-layout="{PhotosetLayout}">
                          {block:Photos}
                             <figure class="tmblr-full"> 
                                 <img class="npf_image" alt="{PhotoAlt}" src="{PhotoURL-500}" data-orig-width="{PhotoWidth-HighRes}" data-orig-height="{PhotoHeight-HighRes}" data-highres="{PhotoURL-HighRes}">
                             </figure>
                          {/block:Photos}
                       </div>
                      {/block:Photoset}
                                                
                      {block:Quote}
                        <p class="npf_quote {Length}">{Quote}</p>
                      {block:Source}<p class="source">&mdash; {Source}</p>{/block:Source}
                      {/block:Quote}
                      
                      {block:Link}
                         <div class="npf-link-block {block:Thumbnail}has-poster not-{/block:Thumbnail}no-poster">
                            <a href="{URL}" {Target}>{block:Thumbnail}
                                <div class="poster" style="background-image: url({Thumbnail-HighRes});">{/block:Thumbnail}
                                <div class="title">{Name}</div>{block:Thumbnail}
                                </div>{/block:Thumbnail}
                        <div class="bottom">{block:Excerpt}<div class="description">{Excerpt}</div>{/block:Excerpt}{block:Host}<div class="site-name">{Host}</div>{/block:Host}</div></a></div>
                     {/block:Link}
                     
                     {block:Chat}{block:Title}<h1>{Title}</h1>{/block:Title}{block:Lines} <p class="npf_chat">{block:Label} <b>{Label}</b>{/block:Label}{Line} </p>{/block:Lines}{/block:Chat}
                     {block:Audio}
                       <div class="posts__audio">
                           {block:AudioEmbed}{AudioEmbed-640}{/block:AudioEmbed}
                       </div>
                     {/block:Audio}
                     
                     {block:Video}
                        <div class="posts__video">{Video-700}</div>
                     {/block:Video}
                     
                     {block:Answer}
                        <div class="posts__question">
                           <img class="posts__answerer--img" src="{AskerPortraitURL-64}" alt="">
                                 <div class="posts__answerer--inner">
                                       <div class="posts__question--asker">
                                            {lang:Asker asked 2}
                                        </div>
                                        {Question}
                                </div>
                         </div>                 
                     {block:Answerer}
                         <div class="posts__answerer">
                            <img class="posts__answerer--img" src="{AnswererPortraitURL-64}" alt="">
                                <div class="posts__answerer--inner">
                                    <div class="posts__answerer--asker">
                                        {Answerer} replied
                                    </div>
                                    {Answer}
                                </div>
                        </div>
                    {/block:Answerer}
                    {/block:Answer}                                            
                    </section>
                    
                    <section class="posts__body">
                    {block:RebloggedFrom}{block:Reblogs}
                        <div class="reblog-list">
                           <div class="reblog-post-avatar">
                              {block:HasAvatar}
                                <img src="{PortraitURL-64}" />
                                      <span class="reblog-post-avatar-name">
                                         {block:IsActive}
                                            {block:HasPermalink}
                                            <a href="{Permalink}" class="user-blog">
                                            {/block:HasPermalink}
                                                {Username}
                                            {block:HasPermalink}
                                            </a>
                                            {/block:HasPermalink}
                                         {/block:IsActive}
                                         {block:IsDeactivated}
                                            {block:HasPermalink}
                                            <a href="{Permalink}" class="user-blog is-deactivated">
                                            {/block:HasPermalink}
                                                {Username}
                                            {block:HasPermalink}
                                            </a>
                                            {/block:HasPermalink}
                                        {/block:IsDeactivated}
                                     </span>
                              {/block:HasAvatar} 
                            </div>
                            {Body}
                         </div>
                         
                         {/block:Reblogs}{/block:RebloggedFrom}
                            {block:NotReblog}
                               <div class="original">
                               {block:Text}{Body}{/block:Text}{block:Photo}{block:Caption}{Caption}{/block:Caption}{/block:Photo}{block:Panorama}{block:Caption}{Caption}{/block:Caption}{/block:Panorama} 
                               {block:Photoset}<div class="npf_photoset" data-layout="{PhotosetLayout}"> {block:Photos} <figure class="tmblr-full"> <img class="npf_image" alt="{PhotoAlt}" src="{PhotoURL-500}" data-orig-width="{PhotoWidth-HighRes}" data-orig-height="{PhotoHeight-HighRes}" data-highres="{PhotoURL-HighRes}"></figure>{/block:Photos}</div>{block:Caption}{Caption}{/block:Caption}{/block:Photoset}{block:Link}{block:Description}{Description}{/block:Description}{/block:Link}{block:Audio}{block:Caption}{Caption}{/block:Caption}{/block:Audio}{block:Video}{block:Caption}{Caption}{/block:Caption}{/block:Video}{block:Answer}{Answer}{/block:Answer}
                            </div>
                    {/block:NotReblog}
                    {block:Actions}
                     <div class="post-cta-action | margin--bottom-15">
                       <a class="btn btn__full btn__primary" href="{url}" rel="nofollow noreferrer noopener" target="_blank">{text}</a>
                     </div>
                    {/block:Actions}
                  </section>
                  
                  {block:Submission}
                    <section class="posts__submitter">
                      <a href="{SubmitterURL}">{Submitter}</a> {block:English}submitted to{/block:English}{block:German}eingereicht bei{/block:German}{block:French}a proposé ce billet à{/block:French}{block:Italian}ha inviato a{/block:Italian}{block:Japanese}からのゲスト投稿{/block:Japanese}{block:Turkish}bu gönderimi{/block:Turkish}{block:Spanish}ha enviado una colaboración a{/block:Spanish}{block:Russian}отправил(а) пост в блог{/block:Russian}{block:Polish}przesłał(a) post do{/block:Polish}{block:PortuguesePT}enviou para{/block:PortuguesePT}{block:PortugueseBR}enviou para{/block:PortugueseBR}{block:Dutch}heeft bijgedragen aan{/block:Dutch}{block:Korean}님이{/block:Korean}{block:ChineseSimplified}已提交给{/block:ChineseSimplified}{block:ChineseTraditional}已送出到{/block:ChineseTraditional}{block:ChineseHK}已提交到{/block:ChineseHK}{block:Indonesian}mengirim ini ke{/block:Indonesian}{block:Hindi}ने{/block:Hindi} {Name} {block:Turkish}bloguna yolladı{/block:Turkish}{block:Korean}님에게 전송했습니다{/block:Korean}{block:Hindi}को सबमिट किया{/block:Hindi}
                    </section>
                  {/block:Submission}
                  {block:Date} 
                  <section class="posts__bottom">
                    <div class="posts__bottom__tags {select:Posts Tags}">
                            {block:HasTags}
                                <a href="#" class="posts__bottom__tags-btn">
                                    <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><line x1="4" y1="9" x2="20" y2="9"></line><line x1="4" y1="15" x2="20" y2="15"></line><line x1="10" y1="3" x2="8" y2="21"></line><line x1="16" y1="3" x2="14" y2="21"></line></svg>
                                 </a>
                                <ul>
                                    {block:Tags}
                                    <li><a href="{TagURL}">#{Tag}</a></li> 
                                    {/block:Tags}
                                </ul>
                            {/block:HasTags}
                     </div>
                     
                     <div class="posts__bottom__action">
                         <ul>
                              <li><a href="{ReblogURL}">
                                    <svg fill="currentColor" viewBox="0 0 17 18.1">
                                        <path d="M12.8.2c-.4-.4-.8-.2-.8.4v2H2c-2 0-2 2-2 2v5s0 1 1 1 1-1 1-1v-4c0-1 .5-1 1-1h9v2c0 .6.3.7.8.4L17 3.6 12.8.2zM4.2 17.9c.5.4.8.2.8-.3v-2h10c2 0 2-2 2-2v-5s0-1-1-1-1 1-1 1v4c0 1-.5 1-1 1H5v-2c0-.6-.3-.7-.8-.4L0 14.6l4.2 3.3z"></path>
                                      </svg>
                                    </a></li>
                                <li><a class="like">{LikeButton}
                                <svg fill="currentColor" viewBox="0 0 20 18"><path d="M14.658 0c-1.625 0-3.21.767-4.463 2.156-.06.064-.127.138-.197.225-.074-.085-.137-.159-.196-.225C8.547.766 6.966 0 5.35 0 4.215 0 3.114.387 2.162 1.117c-2.773 2.13-2.611 5.89-1.017 8.5 2.158 3.535 6.556 7.18 7.416 7.875A2.3 2.3 0 0 0 9.998 18c.519 0 1.028-.18 1.436-.508.859-.695 5.257-4.34 7.416-7.875 1.595-2.616 1.765-6.376-1-8.5C16.895.387 15.792 0 14.657 0h.001zm0 2.124c.645 0 1.298.208 1.916.683 1.903 1.461 1.457 4.099.484 5.695-1.973 3.23-6.16 6.7-6.94 7.331a.191.191 0 0 1-.241 0c-.779-.631-4.966-4.101-6.94-7.332-.972-1.595-1.4-4.233.5-5.694.619-.475 1.27-.683 1.911-.683 1.064 0 2.095.574 2.898 1.461.495.549 1.658 2.082 1.753 2.203.095-.12 1.259-1.654 1.752-2.203.8-.887 1.842-1.461 2.908-1.461h-.001z"></path></svg></a></li>
                          </ul>
                     </div>
                  </section>
                  {/block:Date} 
                  
                 </article>
                 
                 {block:PermalinkPagination}
                     <nav class="pagination | margin--bottom-50 padding--x-15">
                        <div class="pagination__inner | flex flex--align-center flex--justify-between w-100">
                            <a {block:PreviousPost}href="{PreviousPost}" class="is-link"{/block:PreviousPost}><i class="las la-angle-left"></i> {lang:Previous post}</a>
                            <a {block:NextPost}href="{NextPost}" class="is-link"{/block:NextPost}>{lang:Next post} <i class="las la-angle-right"></i></a>
                        </div>
                    </nav>
                 {/block:PermalinkPagination}
                    
                 {block:PermalinkPage}
                    {block:IfDisqusShortname}
                        <article class="posts posts__perma | margin--bottom-5" id="posts-disqus">
                            <div class="posts__perma__info">
                                <h3>{lang:Blog comments powered by Disqus}</h3>
                            </div>
                            <style>#disqus_recommendations {display:none!important;}</style>
                            <div id="disqus_thread"></div>
                            <script type="text/javascript">
                                var disqus_shortname = '{text:Disqus Shortname}'; 
                                var disqus_url = '{Permalink}'; 
                            
                                (function() {
                                    var dsq = document.createElement('script'); 
                                    dsq.type = 'text/javascript'; 
                                    dsq.async = true;
                                    dsq.src = '//' + disqus_shortname + '.disqus.com/embed.js';
                                    (document.getElementsByTagName('head')[0] || document.getElementsByTagName('body')[0]).appendChild(dsq);
                                })();
                            </script>
                            <noscript>Please enable JavaScript to view the <a href="http://disqus.com/?ref_noscript">{lang:Blog comments powered by Disqus}</a></noscript>
                        </article>
                    {/block:IfDisqusShortname}
                     
                    {block:Date} 
                           <article class="posts posts__perma posts__perma__tumblr" data-notes-url="{PostNotesURL}" id="notes">
                               <div class="posts__perma__info">
                                   <h3>{lang:Posted on DayOfWeek DayOfMonth Month Year}</h3>
                                   <div class="posts__perma__data">
                                       {block:RebloggedFrom}
                                       <div class="posts__perma__data-blog">
                                            <img src="{ReblogRootPortraitURL-128}" alt="{ReblogRootName}"><span>Original from
                                           <br>
                                           <a href="{ReblogRootURL}">{ReblogRootName}</a></span>
                                          
                                       </div>
                                       {/block:RebloggedFrom}
                                       
                                       {block:RebloggedFrom} 
                                       <div class="posts__perma__data-blog">
                                           <img src="{ReblogParentPortraitURL-128}" alt="{ReblogParentName}">
                                           <span>{lang:Reblogged from}
                                           <br>
                                           <a href="{ReblogParentURL}">{ReblogParentName}</a></span>
                                            
                                       </div>
                                       {/block:RebloggedFrom}
                                       
                                       {block:NotReblog}
                                       <div class="posts__perma__data-blog">
                                           <img src="{PortraitURL-128}" alt="{Name}">
                                           <span>Originally from
                                           <br>
                                           <a href="{Name}.tumblr.com/">{Name}</a></span>
                                       </div>
                                       {/block:NotReblog}
                                </div>
                            </div>
                            
                            {PostNotes-64}

                           </article>
                           {/block:Date} 
                    {/block:PermalinkPage}    
                    {/block:Posts}
               </div>
               
              {block:Pagination}
                <nav class="pagination">
                    <div class="pagination__info">
                        {lang:Page CurrentPage of TotalPages}
                    </div>
                    <div class="pagination__inner">
                        <a {block:PreviousPage}href="{PreviousPage}" class="is-link"{/block:PreviousPage}><i class="las la-angle-left"></i> {lang:Previous page}</a>
                             
                        {block:JumpPagination length="4"}
                            {block:CurrentPage}
                                <a class="is-current">{PageNumber}</a>
                            {/block:CurrentPage}
                                    
                            {block:JumpPage}
                                <a class="is-jump" href="{URL}">{PageNumber}</a>
                            {/block:JumpPage}
                                
                        {/block:JumpPagination}
                            
                        <a {block:NextPage}href="{NextPage}" class="is-link is-next"{/block:NextPage}>{lang:Next page} <i class="las la-angle-right"></i></a>
                    </div>
                </nav>
            {/block:Pagination}
            
            </section>
            
            {block:IndexPage}
            <div class="wrapper__back-to-top {select:Back To Top Button}">
               <a href="#" class="wrapper__back-to-top__btn"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M12 19V6M5 12l7-7 7 7"/></svg></a>
            </div>
            {/block:IndexPage}
            
        </div>
        
        <div class="wrapper__footer {select:Footer Visibility}" style="background-image: var(--footer-bg-img);">
        {block:HasPages}
            <div class="wrapper__footer__additional {select:Footer Navigation Visibility} | container--width-xl margin--x-auto">
               <ul class="wrapper__footer__additional__links">
                 {block:Pages}<li><a href="{URL}">{Label}</a></li>{/block:Pages}
               </ul>
         </div>
         {/block:HasPages}
        </div>
        
    </main>
    
    <footer class="footer">
      <div class="footer__inner | container--width-xl margin--x-auto">
          <div class="footer__copyright">
              Copyright © {Name} {CopyrightYears}. All rights reserved.
          </div>
          <div class="footer__credit sparkling">
              <a href="https://www.tumblr.com/theme/41159">Nyiur Theme</a> by <a href="https://fukuo.tumblr.com">Fukuo</a>. Powered by <a href="https://tumblr.com/" data-font="tumblr" aria-label="Tumblr"><svg class="svg-logo logo-tumblr" width="55px" viewBox="0 0 245 50" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink"><g class="logotype" stroke="none" stroke-width="1" fill="currentColor" fill-rule="evenodd"><path d="M28.087 49.57h-8.286c-7.461 0-13.021-3.835-13.021-13.01V21.863H0v-7.957C7.461 11.97 10.582 5.556 10.94 0h7.749v12.616h9.04v9.248h-9.04v12.795c0 3.836 1.937 5.162 5.022 5.162h4.376v9.749zm143.951.43c-3.766 0-7.246-1.254-10.151-3.692v3.262h-11.372V7.993h-4.95V0h17.075v15.305c2.224-1.72 5.919-3.119 9.613-3.119 10.51 0 15.676 7.312 15.676 18.46 0 11.612-5.56 19.354-15.89 19.354zm18.115-.43v-7.921h4.197V7.993h-4.95V0h16.93v41.649h4.377v7.92h-20.554zm-112.456 0v-7.921h4.197V20.68h-4.95v-8.065H92.26V17.6c2.582-3.549 7.39-5.413 11.765-5.413 5.525 0 9.22 2.223 11.658 5.914 1.938-3.261 6.529-5.914 12.125-5.914 11.335 0 14.205 8.961 14.205 16.56v12.903h4.125v7.92h-20.16v-7.92h4.054V27.348c0-3.047-1.04-5.628-5.309-5.628-5.273 0-6.816 4.122-6.816 6.13v13.799h4.233v7.92h-20.267v-7.92H106V27.348c0-3.047-.86-5.628-5.093-5.628-5.238 0-6.96 4.122-6.96 6.13v13.799h4.162v7.92H77.697zm137.494 0v-7.921h4.09V20.68h-4.449v-8.065h15.39v5.341c1.9-3.548 6.133-5.77 10.725-5.77H245V22.76h-5.022c-3.766 0-8.717 1.541-8.717 8.566V41.65h4.126v7.92H215.19zM47.53 50c-11.765 0-14.348-8.853-14.348-14.552V12.616h12.411v22.33c0 3.083.754 5.52 4.807 5.52 6.313 0 7.246-4.695 7.246-5.807V20.681h-4.807v-8.065h16.86V41.65h3.55v7.92H59.296V44.91C56.641 48.172 51.762 50 47.529 50zm121.926-8.996c1.902-.215 6.278-.538 6.278-10.287 0-6.774-2.978-9.498-6.35-9.498-2.905 0-7.102 1.54-7.102 10.25 0 7.24 3.551 9.535 7.174 9.535z" fill-rule="evenodd"></path></g></svg></a>
          </div>
      </div>
   </footer>

    <!-- tooltip -->
    <script src="https://unpkg.com/@popperjs/core@2"></script>
    <script src="https://unpkg.com/tippy.js@6"></script>

    <!-- slider  -->
    <script src="https://cdnjs.cloudflare.com/ajax/libs/tiny-slider/2.9.2/min/tiny-slider.js"></script>

    <!-- photosets -->
    <script src="https://cdn.jsdelivr.net/gh/boscoxvi/npfphotosets@master/npfphotosets.js"></script>
    
    <!-- toggle -->
    <script src="https://cdn.jsdelivr.net/gh/ericbutler555/plain-js-slidetoggle@master/slideToggle.min.js"></script>
    
    <!-- masonry -->
    <script src="https://unpkg.com/masonry-layout@4/dist/masonry.pkgd.min.js"></script>
    <script src="https://unpkg.com/imagesloaded@4/imagesloaded.pkgd.min.js"></script>

    <!-- main scripts -->
    <script src="https://static.tumblr.com/5ojoydj/PRXs1g7kf/app.min.js"></script>
    <script src="https://static.tumblr.com/5ojoydj/Znmrypjgu/featured.js"></script>
    
    {block:IndexPage}
    <script type="text/javascript" src="https://{Name}.tumblr.com/api/read/json?callback=featured&tagged=featured"></script>
    {/block:IndexPage}
    <script>
        tippy("[title]", {
            arrow: true,
            placement: "top", // top, right, bottom, left
            delay: 5, //ms
            distance: 15, //px or string
            maxWidth: 300, //px or string
    
            // leave these as they are
            followCursor: false,
            allowHTML: true,
            ignoreAttributes: true,
            content(reference) {
              const title = reference.getAttribute("title");
              reference.removeAttribute("title");
              return title;
            },
        });
    </script>
</body>
</html>
