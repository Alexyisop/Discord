@import url('https://anti-betterdocs.github.io/BlockBetterDocs/code.css');
/* markdown adding a background */
.da-app .hljs, .da-app .markup-2BOw-j code, .da-app .markup-2BOw-j code.inline {
	background-color: var(--color-main);
}
/* sending message area adding a background */
.da-app .inner-zqa7da {
	background-color: var(--color-main);
}

/* end */

/* markdown adding border and border radius */
.da-app .hljs, .da-app .markup-2BOw-j code {
	border: 1px solid rgb(214, 28, 25);
	border-radius: 5px;
}

/* sending message area adding a border */
.da-app .inner-zqa7da {
	border: 1px solid rgb(214, 28, 25);
	border-radius: 5px;
	box-shadow: 0px 0px 10px #375ca7;
}

.contentSelectedText-3wUhMi, .contentSelectedVoice-1WDIBM, .channel-2QD9_O.selected-1HYmZZ a {
    background-color: var(--color-main);
    border: 1px solid rgb(214, 28, 25);
    border-bottom-color: #4a79d7;
    border-top-left-radius: 20px;
    border-bottom-right-radius: 20px;
    border-bottom-width: 2.5px;
}
.theme-dark .member-3W1lQa.popout-open .content-OzHfo4, .theme-dark .member-3W1lQa.popout-open:hover .content-OzHfo4 {
    background-color: var(--color-main);
    border: 1px solid rgb(214, 28, 25);
    border-top-left-radius: 20px;
    border-bottom-right-radius: 20px;
    border-bottom-width: 2.5px;
    height: 40px;
    width: 0px;
}
/* connected voice area */
.container-1UB9sr {
	background-color: var(--color-main);
	border: 1px solid rgb(214, 28, 25);
	border-top-left-radius: 20px;
	border-bottom-right-radius: 20px;
}

/* search button at the top */
.theme-dark .search .search-bar {
    background-color: var(--color-main);
    border: 1px solid rgb(214, 28, 25);
}


/* guild add button */
.theme-dark .circleIconButton-jET_ig {
    background: var(--color-main);
    border-color: rgb(180, 11, 2, 0,96);
    color: rgb(55, 92, 167);
}

/* scroll bar */
::-webkit-scrollbar-thumb {
	all: unset!important;
	background-color: rgba(214, 28, 25)!important;
	border: 1px solid rgb(214, 28, 25)!important;
	border-radius: 5px!important;
}

::-webkit-scrollbar-track-piece {
	all: unset!important;
	background-color: transparent!important;
}

/* makes hover effect on some areas from default discord */
.scrollerFade-1Ijw5y .scroller-2FKFPG:hover::-webkit-scrollbar-thumb, .scrollerFade-1Ijw5y .scroller-2FKFPG:hover::-webkit-scrollbar-track, .scrollerFade-1Ijw5y:hover::-webkit-scrollbar-thumb, .scrollerFade-1Ijw5y:hover::-webkit-scrollbar-track {
    visibility: visible!important;
}
.scrollerFade-1Ijw5y .scroller-2FKFPG::-webkit-scrollbar-thumb, .scrollerFade-1Ijw5y .scroller-2FKFPG::-webkit-scrollbar-track {
    visibility: hidden!important;
}
/* scroll bar removing background on emoji page */
.scrollerThemed-2oenus.themeLight-1_DWyY.scrollerTrack-1ZIpsv>.scroller-2FKFPG::-webkit-scrollbar-track, .theme-dark .scrollerThemed-2oenus.themeLight-1_DWyY.scrollerTrack-1ZIpsv>.scroller-2FKFPG::-webkit-scrollbar-track, .theme-light .scrollerWrap-2lJEkd.scrollerTrack-1ZIpsv>.scroller-2FKFPG::-webkit-scrollbar-track {
    background-color: transparent;
}
/* chat border and backgrounds many changes and positioning */
.large-3ChYtB, .image-33JSyf {
	right: 80px;
}
.theme-dark .timestampCozy-2hLAPV {
	padding-left: 5px;
}
.theme-dark .headerCozyMeta-rdohGq {
	position: relative;
	right: 80px;
}

.theme-dark .headerCozyMeta-rdohGq::after {
	content: '';
    position: absolute;
    left: -16px;
    top: 7px;
    width: 0;
    height: 0;
    border-top: 10px solid transparent;
    border-bottom: 10px solid transparent;
    border-right: 10px solid rgba(214, 28, 25, 0.4);
}

.contentCozy-3XX413, .theme-dark .headerCozyMeta-rdohGq {
    margin-left: 5px;
}

/* disabling divider */
.theme-dark .dividerEnabled-2TTlcf {
	border: none;
}

/* disabling margin between messages */
.message-1PNnaP {
    margin-bottom: 0em;
}

.messageCompact-kQa7ES, .messageCozy-2JPAPA {
	background: rgba(180, 11, 2, 0,96);
	border: 1px solid rgba(214, 28, 25, 0.4);
	margin-right: 7px;
	margin-left: 100px;
	padding-top: 5px;
	padding-bottom: 5px;
	border-radius: 3px;
}
/* public button discord */
#bd-pub-button, .theme-dark .container-2td-dC .wrapper-2lTRaf {
	background-color: var(--color-main);
}
/* guild button */
.theme-dark .container-2td-dC .wrapper-2lTRaf[style*="background-color: rgb(47, 49, 54);"] {
	background-color: var(--color-main)!important;
	box-shadow: rgb(214, 28, 25) 0px 0px 20px;
}

/* invite group */
.theme-dark .wrapper-35wsBm {
    background: rgba(2, 22, 45, 0.8);
    border-color: rgb(214, 28, 25);
}


/* embed urls */
.theme-dark .embedInner-1-fpTo {
    background-color: rgba(19, 82, 93, 0.3);
    border-color: rgb(214, 28, 25);
}
.theme-dark .embedPill-1Zntps {
    background-color: rgb(214, 28, 25);
}

/* emoji menu */

.emojiPicker-3m1S-j, #bda-qem-twitch-container, #bda-qem-favourite-container {
	background-color: rgba(214, 28, 25, 0.9);
}
/* sticky part of emoji area */
.emojiPicker-3m1S-j .stickyHeader-1SS0JU {
    background: rgb(214, 28, 25);
    border: 1px solid #375ca7;
    border-radius: 5px;
}
.diversitySelector-tmmMv0 .popout-2nUePc {
    background: rgba(214, 28, 25, 0.9);
    border: 1px solid #375ca7;
}
.search-bar.search-bar-light {
    background-color: rgba(214, 28, 25, 0.9);
    border: 1px solid #375ca7;
}
.search-bar.search-bar-light .search-bar-inner {
    background-color: rgb(214, 28, 25);
}
#bda-qem button:hover {
    background: rgb(214, 28, 25);
}
#bda-qem {
	background-color: rgba(214, 28, 25, 0.9);
}
#bda-qem button {
    border-left: 1px solid #375ca7;
    border-top: 1px solid #375ca7;
}
#bda-qem-twitch-container, #bda-qem-favourite-container, .emoji-picker, .emojiPicker-3m1S-j {
	 border: 1px solid #375ca7;
}
.emoji-picker, .emojiPicker-3m1S-j {
	border-top: none;
}
#bda-qem button {
    border-left: 1px solid #375ca7;
    box-shadow: #375ca7 1px 0 0 0;
}
#bda-qem button.active {
    background-color: #08294f;
    color: #fff;
}
#bda-qem button {
    color: #99aab5;
    border-left: 1px solid #375ca7;
}
.emojiPicker-3m1S-j .scroller-3vODG7 .emojiItem-109bjA.selected-39BZ4S {
    background-color: #092c53;
    border-color:; #375ca7;
}

.emojiPicker-3m1S-j .categories-1feg4n .item-16cXuq.selected-39BZ4S {
    border-bottom-color: #375ca7;
}

/* custom stuff for emoji page */
.emojiPicker-3m1S-j .stickyHeader-1SS0JU {
    top: 10px;
}
.emojiPicker-3m1S-j .category-2U57w6 {
    position: relative;
    top: -1px;
    height: 29px;
}

.emojiPicker-3m1S-j .scroller-3vODG7 .emojiItem-109bjA {
    position: relative;
    top: 13px;
}
/* end of custom stuff for this area */

/* divider in chat */
.theme-dark .divider-3gKybi:not(.dividerRed-MKoLlr) .dividerContent-2L12VI:after, .theme-dark .divider-3gKybi:not(.dividerRed-MKoLlr) .dividerContent-2L12VI:before {
    border-color: #375ca7;
}
.theme-dark .divider-3gKybi:not(.dividerRed-MKoLlr) .dividerContent-2L12VI {
    color: rgb(214, 28, 25);
}

.theme-dark .hasMore-3e72_v button {
    background: rgba(214, 28, 25, 0.9);
    border: 1px solid #375ca7;
}
.hasMore-3e72_v button {
    color: #375ca7;
}


/* cards */

/* playing a game card */
.theme-dark .body-3iLsc4, .theme-dark .footer-1fjuF6, .theme-dark .body-3ND3kc {
    background-color: rgba214, 28, 25, 0.9);
}
.theme-dark .quickMessage-1yeL4E {
    background-color: rgba(214, 28, 25, 0.9);
    border-color: #375ca7;
}
.headerPlaying-j0WQBV, .da-topSectionPlaying {
    background: rgba(214, 28, 25, 0.9);
    border: 1px solid #0af;
    border-top-left-radius: 10px;
    border-top-right-radius: 10px;
}
/* button for header playing on add friend */
.lookInverted-2D7oAl.colorBrand-3pXr91, .lookFilled-1Gx00P.colorBrand-3pXr91 {
    background-color: rgba(214, 28, 25, 0.9);
    border: 1px solid rgba(214, 28, 25, 0.9);
    color: #ffffff;
}
.lookInverted-2D7oAl.colorBrand-3pXr91:hover, .lookFilled-1Gx00P.colorBrand-3pXr91:hover {
    background-color: rgba(214, 28, 25, 0.9);
}

.userPopout-3XzG_A {
    border: 1px solid #375ca7;
}

/* normal card */
.theme-dark .da-headerNormal, .da-root .da-topSectionNormal {
    background-color: rgba(214, 28, 25, 0.9);
}


/* spotify card */
.da-headerSpotify, .da-topSectionSpotify {
	background: rgba(214, 28, 25, 0.9);
    border: 1px solid rgba(214, 28, 25, 0.9);
}

/* on call area */
.video-1FfuMD {
    background-color: rgba(214, 28, 25, 0.9);
    border: 1px solid #375ca7;
}
.theme-dark .wrapper-29NfPK.minimum-2d6zH6 .actions-2vadYq .center-1Vp33r {
    background-color: #08294d;
    border-color: #375ca7;
}

/* fixing idle and other states *//*
.idle-3DEnRT, .status-3fQvEa {
	left: 0px;
}*/

/* unread messages */
.wrapper-232cHJ {
    background-color: #33579e;
    box-shadow: 0px 0px 10px #33579e;
}

/* settings my account background */
.theme-dark .da-cardPrimary, .theme-dark .da-cardPrimaryEditable {
	background: rgba(214, 28, 25, 0.3);
	border-color: rgba(214, 28, 25, 0.4);
}

/* settings button normal and hover of categories */
.da-app .side-8zPYf6 .da-itemSelected, .theme-dark #bd-settings-sidebar .ui-tab-bar-item.selected, .theme-dark .side-8zPYf6 .themed-OHr7kt.selected-3s45Ha.item-PXvHYJ, .theme-dark .side-8zPYf6 .themed-OHr7kt.selected-3s45Ha.item-PXvHYJ, .theme-dark .side-8zPYf6 .themed-OHr7kt.selected-3s45Ha.item-PXvHYJ:hover {
    background-color: #08294f;
   	border: 1px solid #375ca7;
	border-top-left-radius: 20px;
	border-bottom-right-radius: 20px;
}
.da-app .side-8zPYf6 .da-itemDefault:hover, .da-app .da-wrapperHoveredText .da-content, .da-app .da-channel:hover a, .theme-dark #bd-settings-sidebar .ui-tab-bar-item:hover, .theme-dark .side-8zPYf6 .themed-OHr7kt.item-PXvHYJ:hover {
	background-color: rgba(214, 28, 25, 0.63);
   	border: 1px solid #375ca7;
	border-top-left-radius: 20px;
	border-bottom-right-radius: 20px;
}
.theme-dark .member-3W1lQa:hover .content-OzHfo4 {
	background-color: rgba(214, 28, 25, 0.63);
   	border: 1px solid #375ca7;
	border-top-left-radius: 20px;
	border-bottom-right-radius: 20px;
	height: 40px;
    width: 0px;
}

/* secondary buttons */
.da-app .lookFilled-1Gx00P.colorBrand-3pXr91 {
	b…
