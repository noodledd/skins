/* Imports */
@import "https://monstrousdev.github.io/themes/phoenix-bundle/base.css";


/* Variables */

:root {
  --theme-name: "Reborn";
  --blackout: black;
  --dark: #333;
  --lighter: #666;
  --bright: #ccc;
  --background-blur: 0px;
  --popup-blur: 0px;
}

  /* Dark Mode */
  .theme-dark,
  .appMount-3lHmkl {
    --primary-color: rgba(0,0,0,0.75);
    --secondary-color: rgba(0,0,0,0.6);
    --tertiary-color: rgba(0,0,0,0.4);
    --quaternary-color: rgba(0,0,0,0.7);
  }

  /* Light Mode */
  .theme-light {
    --primary-color: rgba(0,0,0,0.55);
    --secondary-color: rgba(0,0,0,0.4);
    --tertiary-color: rgba(0,0,0,0.2);
    --quaternary-color: rgba(0,0,0,0.5);
  }

/* Table of Contents 
 ============== STATIC ===============
1. Backgrund
  1.a. Main Background
  1.b. Transparency
2. User Settings
3. Chat
4. Popouts and Modals
5. @Media Edits
6. Misc
*/





/* 1. Background */
  /* 1.a. Main Background */
  .appMount-3lHmkl::before {
    position: absolute;
    content: " ";
    height: 100%;
    width: 100%;
    background-image: var(--background-image);
    background-size: cover;
    background-repeat: no-repeat;
    background-position: center;
    pointer-events: none;
    filter: blur(var(--background-blur));
  }
  
  .app-2rEoOp {
    background-color: var(--primary-color);
  }
  
    /* 1.b. Transparency */
  .layer-3QrUeG, 
  .layers-3iHuyZ,
  .container-2lgZY8,
  .standardSidebarView-3F1I7i .contentRegion-3nDuYy,
  .channels-Ie2l6A, 
  .container-PNkimc,
  .members-1998pB,
  .chat-3bRxxu, 
  .chat-3bRxxu form, 
  .content-yTz4x3,
  .messagesWrapper-3lZDfY,
  .noChannel-Z1DQK7,
  .private-channel-call,
  .video-1FfuMD,
  #friends,
  .appMount-3lHmkl,
  .standardSidebarView-3F1I7i,
  .standardSidebarView-3F1I7i .sidebarRegion-VFTUkN,
  .inner-zqa7da,
  .standardSidebarView-3F1I7i .sidebarRegion-VFTUkN .sidebar-CFHs9e,
  .userSettingsVoice-iwdUCU .media-engine-video,
  .activityFeed-28jde9,
  .search .searchBarIcon-1J6sKG,
  .footer-2yfCgX,
  .container-1UB9sr,
  .title-3qD0b-,
  .header-2o-2hj,
  .headerBar-UHpsPw,
  .container-2Thooq,
  .privateChannels-1nO12o .search-bar,
  .wrapper-2NJDcI,
  .wrapper-29NfPK,
  .incomingCall-14zLc,
  .gameLibrary-TTDw4Y,
  .paginator-166-09,
  .payment-xT17Mq,
  .sidebar-1-SQro,
  .reactors-Blmlhw,
  .applicationStore-1pNvnv,
  #permissions-modal-wrapper .role-side,
  .itemBackground-1jfD8p,
  .gamePreview-9weYR2 .sideBar-2_lxpG,
  .gamePreview-9weYR2 .body-1SVoBw,
  .news-2KwXHF,
  .root-1BQpZw,
  .root-26DmKJ,
  .container-3gCOGc,
  .appMount-3lHmkl .pageWrapper-1PgVDX,
  .wrapper-1Rf91z,
  .emptyPlayers-dx3qig, 
  .players-1zg2l8,
  .users-i_3-kL,
  #app-mount .container-1r6BKw,
  #app-mount .wrapper-1Rf91z .scrollerWrap-1IAIlv .scroller-2TZvBN>.listItem-2P_4kh:first-child,
  #app-mount .users-i_3-kL,
  #app-mount .footer-1FPmkC,
  #app-mount .footer-30ewN8,
  .searchBar-1MOL6S, 
  #app-mount .container-2XeR5Z,
  #app-mount .footer-3rDWdC,
  #app-mount .privateChannels-1nO12o,
  #app-mount .panels-j1Uci_,
  #app-mount .scroller-2TZvBN,
  #app-mount .scroller-1JbKMe,
  #app-mount .sidebar-2K8pFh,
  .scrollableContainer-38zsVD,
  .scrollableContainer-2NUZem {
  background: transparent !important;
  }
  
  #app-mount .footer-3rDWdC {
    box-shadow: none;
  }

  #app-mount .bannerImage-1jOskm::after {
    opacity: 0;
  }
  
  #app-mount .activityFeed-1C0EmJ {
    background-color: transparent;
  }
  
  .typeMacOS-3EmCyP.titleBar-AC4pGV,
  .uploadModal-2ifh8j .footer-3mqk7D {
    background-color: var(--primary-color) !important;
  }
  
  
  /* 2. User Settings */
  .standardSidebarView-3F1I7i .sidebarRegion-VFTUkN .sidebarRegionScroller-3MXcoP,
  .uploadModal-2ifh8j .footer-3mqk7D,
  .uploadModal-2ifh8j .inner-3nWsbo .channelTextAreaUpload-3t7EIx .inner-zqa7da {
    background-color: var(--secondary-color) !important;
  }
  
  
  
  /* 3. Chat */
  .searchResultsWrap-2DKFzt,
  .searchPopout-1vUlP3,
  #app-mount .container-16j22k {
    background: linear-gradient(var(--primary-color), var(--primary-color)), var(--background-image) center/cover no-repeat !important;
    background-attachment: fixed;
  }

  .content-3dzVd8 .innerNoAutocomplete-1WpcVO {
    background-color: var(--tertiary-color) !important;
  }

  /* 4. Popouts & Modals */
  .colorPickerCustom-2CWBn2 {
    border-color: var(--quaternary-color) !important;
  }
  
  .select-2TCrqx .Select-menu-outer,
  #app-mount .popout-3G62UL {
    background-color: transparent !important;
    background-attachment: fixed !important;
    background-image: var(--background-image) !important;
    background-position: center !important;
    background-size: cover !important;
  }
  
  .Select .Select-menu {
    background-color: var(--primary-color);
  }
  
  .botTagInvert-18-95s {
    background-color: var(--main-color);
    color: white;
  }
  
  #app-mount .searchResultsContainer-1ma_dc,
  #app-mount .menu-Sp6bN1,
  #app-mount .themedPopout-25DgLi,
  #app-mount .container-3ayLPN,
  #app-mount .addGamePopout-2RY8Ju,
  #app-mount .colorPickerCustom-2CWBn,
  #app-mount .perksModal-fSYqOq {
    background: linear-gradient(var(--primary-color), var(--primary-color)),var(--background-image) center/cover no-repeat fixed !important;
  }

  #app-mount .messagesPopoutWrap-1MQ1bW {
    background: linear-gradient(var(--primary-color), var(--primary-color)),var(--background-image) center/cover no-repeat !important;
  }

  #app-mount .css-1rckt42-menu {
    background: linear-gradient(var(--quaternary-color), var(--quaternary-color)), var(--background-image) center/cover no-repeat;
    background-attachment: fixed !important;
  }

  #app-mount .tierMarkerBackground-3q29am {
    background: linear-gradient(var(--primary-color), var(--primary-color)), var(--popup-background) center/600px 618px no-repeat !important;
    background-attachment: fixed;
  }

  .emojiPicker-3m1S-j, 
  .emojiPicker-3m1S-j .dimmer-3iH-5D.visible-3k45bQ, 
  .diversitySelector-tmmMv0 .popout-2nUePc,
  #app-mount .uploadModal-2ifh8j {
  background: linear-gradient(var(--primary-color), var(--primary-color)), var(--popup-background) center/cover no-repeat !important;
  }

  .emojiPicker-3m1S-j .categories-1feg4n,
  .infoBar-U6oBFk {
    background: var(--tertiary-color);
  }
  
  .userPopout-3XzG_A,
  .create-guild-container.deprecated,
  .inner-1JeGVc .root-SR8cQa,
  .container-2x5lvQ,
  .container-2Yth53,
  .userList-1kLH8B,
  #permissions-modal-wrapper #permissions-modal,
  .create-guild-container-new.deprecated .form.deprecated,
  .toast,
  .inner-2VEzy9 .root-SR8cQa,
  #app-mount .modal-3c3bKg .inner-1ilYF7 .root-SR8cQa {
    background-image: var(--popup-background) !important;
    background-size: cover !important;
    background-repeat: no-repeat !important;
    background-position: center !important;
  }
  
  #app-mount .quickswitcher-3JagVE,
  #app-mount .modal-3HD5ck,
  #app-mount .keyboardShortcutsModal-3piNz7,
  #app-mount .incomingCallInner-2VmFiR,
  #app-mount .regionSelectModal-12e-57,
  .backdrop-1wrmKB[style*="background-color: rgb(255, 255, 255)"],
  #app-mount .gamePreview-9weYR2,
  #app-mount .popout-2xBvMR,
  #app-mount .sb-menu-scroller-wrapper,
  .metalloriff-changelog-scroller,
  .container-VSDcQc,
  .bd-modal-inner,
  #app-mount .contextMenu-HLZMGh,
  #app-mount .monsterModal,
  #app-mount .popout-3sVMXz .container-jGk-CT,
  #app-mount .modal-3v8ziU,
  #app-mount .modal-yWgWj- {
  background: linear-gradient(var(--primary-color), var(--primary-color)), var(--popup-background) center/cover no-repeat !important;
  }

  #app-mount .content-3CCvMx:before {
    background-color: var(--quaternary-color);
  }
  
  .container-2Yth53 {
    border-radius: 5px;
  }
  
  #app-mount .popout-3G62UL::before {
    border-radius: 4px;
  }
  
  .userPopout-3XzG_A .header-2BwW8b,
  [class*="topSection"],
  .tiles-2aXG_k,
  .container-2x5lvQ header,
  .container-2x5lvQ section,
  #permissions-modal-wrapper .header,
  #permissions-modal-wrapper .modal-body {
    background-color: var(--primary-color) !important;
  }
  
  .create-guild-container.deprecated .form.deprecated .form-inner {
    background-color: var(--quaternary-color) !important;
  }
  
  .searchPopout-1vUlP3::before,
  .add-game-popout::before,
  .toast::before,
  #app-mount .popout-3G62UL::before {
    content: "";
    position: absolute;
    height: 100%;
    width: 100%;
    top: 0;
    left: 0;
    background-color: var(--primary-color);
    pointer-events: none;
  }
  
  .container-16j22k::before,
  .toast::before,
  #app-mount .popout-3G62UL::before {
    z-index: -1 !important;
  }
  
  .notches-1sAcEM {
    position: relative;
    background-attachment: fixed;
    background-image: var(--background-image) !important;
    background-position: center;
    background-size: cover;
    background-repeat: no-repeat;
    -webkit-mask-image: url("data:image/svg+xml;charset=utf-8,<svg%20xmlns='http://www.w3.org/2000/svg'%20width='8'%20height='20'%20fill='%2336393f'><path%20fill-rule='evenodd'%20d='M0%200h8v20H0V0zm4%202a2%202%200%200%200-2%202v12a2%202%200%201%200%204%200V4a2%202%200%200%200-2-2z'/></svg>");
    -webkit-mask-repeat: repeat-x;
    width: 100%;
  }
  
  .notches-1sAcEM::before {
    content: '';
    position: absolute;
    top: 0;
    left: 0;
    height: 100%;
    width: 100%;
    -webkit-mask-image: url("data:image/svg+xml;charset=utf-8,<svg%20xmlns='http://www.w3.org/2000/svg'%20width='8'%20height='20'%20fill='%2336393f'><path%20fill-rule='evenodd'%20d='M0%200h8v20H0V0zm4%202a2%202%200%200%200-2%202v12a2%202%200%201%200%204%200V4a2%202%200%200%200-2-2z'/></svg>");
    -webkit-mask-repeat: repeat-x;
    background-color: var(--primary-color);
  }
  
  .content-1_NQ-_,
  .errorState-3QMR6P,
  .phoneVerificationModal-OzcDc3 .title-3qNdae,
  .phoneVerificationModal-OzcDc3 .description-3JBgvQ,
  .container-_CzRhL img[src*="/assets/261873897d8899d4e2e724efdfa21ee3.svg"],
  .container-_CzRhL .title-Ic5R7V,
  .container-_CzRhL .description-2waT7u,
  .tipsWithoutResults-lGY-De, 
  .tipsWithResults-HhTE9b,
  .modalTitle-37O4n6,
  .modalSubtitle-1Pj5nv,
  .queryText-3xoOY7,
  .empty-3sCt5f,
  .popoutSocialInfo-1qhqSY,
  .recommendationReason-21q3aC,
  .themeDark-3Ap_7i,
  .sb-menu-label,
  .sb-menu-scroller,
  .metalloriff-update-label,
  .metalloriff-changelog-label,
  .emptyState-2gL-9T,
  .container-16j22k * {
    z-index: 1;
  }
  
  .emptyNote-3nZbCz, 
  .emptyTitle-3Jm6Ve {
    color: white !important;
    z-index: 2;
    opacity: 1;
   }
  
  .popout-3sVMXz .themedPopout-25DgLi .header-SsaQ8X {
    background-color: var(--tertiary-color) !important;
  }
  
  .need-help-modal .header h1::after {
    left: -220px;
  }

  .layer-v9HyYc[style*="; bottom: 5"][id*="popout_"] .menu-Sp6bN1 .itemBase-1Qj4z6:nth-child(7) {
    background: linear-gradient(var(--primary-color), var(--primary-color)),var(--background-image) center/cover no-repeat fixed !important;
  }
  
  /* 5. @Media Edits */
  @media only screen and (max-width: 915px) {
  
    .members-1998pB:hover {
      background-color: var(--primary-color) !important;
    }
  }

/* 6. Misc */
#ghostping-panel {
  background-image: linear-gradient(var(--primary-color), var(--primary-color)), var(--background-image) !important;
  background-size: cover, cover;
  background-position: center, center;
  background-attachment: initial, fixed;
}
