<!DOCTYPE html>
<html lang="en" class="content-en_us en_us  touchPageRenderingFix pageAnalytics" data-language="en_us" data-page-path="/content/developers/website/languages/en/tutorials/build-apps-workflow-trigger" data-country-code="glo" data-every-page-analytics-page-name="dev:/tutorials/build-apps-workflow-trigger.html" data-page-section="tutorials" data-page-model-path="/tutorials/build-apps-workflow-trigger.model.json" data-is-publish xmlns="http://www.w3.org/1999/xhtml" prefix="og: http://ogp.me/ns# fb: http://www.facebook.com/2008/fbml" data-request-path="/content/developers/website/languages/en/tutorials/build-apps-workflow-trigger" data-header-model-path="/bin/sapdxc/cache/header/content/developers/website/languages/en/_jcr_content/parHeader/headerstandard.model.json">
    <head>
        <meta http-equiv="content-type" content="text/html; charset=UTF-8"/>
        <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
        <meta http-equiv="X-UA-Compatible" content="IE=edge"/>
        <title>Create SAP Build App to Trigger Workflow | Tutorials for SAP Developers</title>
        <meta name="description" content="Trigger a workflow created in SAP Build Process Automation from an app created with SAP build Apps."/>
        <meta name="imsId" content="19285"/>
        <meta name="taskType" content="c1a376dd-ebd0-4787-804e-a23fef23ba06:b79e26e3-025a-455b-a9e5-3047ed76bad2/f27745cc-3391-40c9-85b6-53153cb8c387"/>
        <meta name="duration" content="PT25M"/>
        <meta property="og:type" content="website"/>
        <meta property="og:url" content="https://developers.sap.com/tutorials/build-apps-workflow-trigger.html"/>
        <meta property="og:title" content="Create SAP Build App to Trigger Workflow | SAP"/>
        <meta property="og:description" content="Trigger a workflow created in SAP Build Process Automation from an app created with SAP build Apps."/>
        <meta property="og:site_name" content="SAP"/>
        <meta property="og:image" content="http://developers.sap.com/dam/application/shared/logos/sap_logo_rgb_onwhite_0300_0300.png.adapt.png/1656382976488.png"/>
        <meta name="twitter:card" content="summary"/>
        <meta name="twitter:url" content="https://developers.sap.com/tutorials/build-apps-workflow-trigger.html"/>
        <meta name="twitter:title" content="Create SAP Build App to Trigger Workflow | SAP"/>
        <meta name="twitter:description" content="Trigger a workflow created in SAP Build Process Automation from an app created with SAP build Apps."/>
        <meta name="twitter:site" content="@SAPdevs"/>
        <meta name="twitter:image" content="http://developers.sap.com/dam/application/shared/logos/sap_logo_rgb_onwhite_0300_0300.png.adapt.png/1656382976488.png"/>
        <link rel="apple-touch-icon" sizes="60x60" href="/etc.clientlibs/sapdx/clientlibs/clientlib-generic-legacy/resources/images/apple-touch-icons/touch-icon-60x60.png"/>
        <link rel="apple-touch-icon" sizes="120x120" href="/etc.clientlibs/sapdx/clientlibs/clientlib-generic-legacy/resources/images/apple-touch-icons/touch-icon-120x120.png"/>
        <link rel="apple-touch-icon" sizes="180x180" href="/etc.clientlibs/sapdx/clientlibs/clientlib-generic-legacy/resources/images/apple-touch-icons/touch-icon-180x180.png"/>
        <link rel="apple-touch-icon" sizes="1024x1024" href="/etc.clientlibs/sapdx/clientlibs/clientlib-generic-legacy/resources/images/apple-touch-icons/touch-icon-1024x1024.png"/>
        <!--*/ Used for metadata customization of inherited pages */-->
        <meta name="sm_tech_ids" content="en-US,636501023871914112130650131163185,73554900100800004334,d64acece-d95f-47a5-9e70-71c487db6c5a,01200615320800003694,9b39e112-292a-4b14-a747-b4fff6b2eec1,73554900100800003832,73555000100700001491"/>
        <meta name="software_product_technology_platform_sap_build" content="SAP Build Apps, enterprise edition"/>
        <meta name="software_product_technology_platform" content="SAP Business Technology Platform"/>
        <meta name="type" content="Page"/>
        <meta name="software_product_technology_platform" content="SAP Build"/>
        <meta name="tutorial" content="Experience"/>
        <meta name="content_format" content="Web Pages"/>
        <meta name="software_product" content="Technology Platform"/>
        <meta name="type" content="Tutorial"/>
        <meta name="web_site_identifier" content="Developer"/>
        <meta name="tutorial_experience" content="Beginner"/>
        <meta name="language" content="English"/>
        <meta name="software_product_technology_platform_sap_build" content="SAP Build Process Automation"/>
        <meta name="software_product_technology_platform_sap_business_technology_platform" content="SAP Business Technology Platform"/>
        <link rel="shortcut icon" type="image/x-icon" href="/favicon.ico"/>
        <link rel="dns-prefetch" href="https://epsilon.6sense.com"/>
        <link rel="preconnect" href="https://epsilon.6sense.com"/>
        <link rel="dns-prefetch" href="https://assets.adobedtm.com"/>
        <link rel="preconnect" href="https://assets.adobedtm.com"/>
        <link rel="dns-prefetch" href="https://sapglobalmarketingin.tt.omtrdc.net"/>
        <link rel="preconnect" href="https://sapglobalmarketingin.tt.omtrdc.net"/>
        <link rel="dns-prefetch" href="https://consent.trustarc.com"/>
        <link rel="preconnect" href="https://consent.trustarc.com"/>
        <link rel="dns-prefetch" href="https://content.cdn.sap.com"/>
        <link rel="preconnect" href="https://content.cdn.sap.com"/>
        <link rel="preload" href="/etc.clientlibs/sapdx/front-layer/dist/resources/assets/fonts/BentonSansLight.woff2" as="font" type="font/woff2" crossorigin/>
        <link rel="preload" href="/etc.clientlibs/sapdx/front-layer/dist/resources/assets/fonts/BentonSansMedium.woff2" as="font" type="font/woff2" crossorigin/>
        <link rel="canonical" href="https://developers.sap.com/tutorials/build-apps-workflow-trigger.html"/>
        <link rel="preload" href="/etc.clientlibs/sapdx/front-layer/dist/resources/assets/fonts/BentonSansBook.woff2" as="font" type="font/woff2" crossorigin/>
        <link rel="preload" href="/etc.clientlibs/sapdx/front-layer/dist/resources/assets/fonts/BentonSansBold.woff2" as="font" type="font/woff2" crossorigin/>
        <link rel="preload" href="/etc.clientlibs/sapdx/front-layer/dist/resources/assets/fonts/BentonSansRegular.woff2" as="font" type="font/woff2" crossorigin/>
        <link href="/etc.clientlibs/sapdx/front-layer/dist/resources/developers-responsive/516.6ca7a513867468f82ee3.css" rel="stylesheet" type="text/css">
        <link href="/etc.clientlibs/sapdx/front-layer/dist/resources/developers-responsive/1638.60708006cccbdeee9357.css" rel="stylesheet" type="text/css">
        <link href="/etc.clientlibs/sapdx/front-layer/dist/resources/developers-responsive/navigation-Footer.9aa7e290745563518720.css" rel="stylesheet" type="text/css">
        <link href="/etc.clientlibs/sapdx/front-layer/dist/resources/developers-responsive/developers-responsive-TutorialPage.497cca8b48dd5dd89723.css" rel="stylesheet" type="text/css">
        <link href="/etc.clientlibs/sapdx/front-layer/dist/resources/developers-responsive/default.141634ed0ecca33eaa3c.css" rel="stylesheet" type="text/css">
        <meta property="developers-adaptive-images-renditions" content="{&#34;queriesOrder&#34;:[&#34;(min-width: 1921px)&#34;,&#34;(min-width: 1300px) and (max-width: 1920px)&#34;,&#34;(min-width: 1300px) and (max-width: 1920px) and (-webkit-min-device-pixel-ratio: 2)&#34;,&#34;(min-width: 980px) and (max-width: 1299px)&#34;,&#34;(min-width: 980px) and (max-width: 1299px) and (-webkit-min-device-pixel-ratio: 2)&#34;,&#34;(min-width: 768px) and (max-width: 979px)&#34;,&#34;(min-width: 768px) and (max-width: 979px) and (-webkit-min-device-pixel-ratio: 2)&#34;,&#34;(min-width: 768px) and (max-width: 1023px)&#34;,&#34;(min-width: 768px) and (max-width: 1023px) and (-webkit-min-device-pixel-ratio: 2)&#34;,&#34;(max-width: 767px)&#34;,&#34;(max-width: 767px) and (-webkit-min-device-pixel-ratio: 2)&#34;],&#34;imageConfig&#34;:{&#34;Image_component&#34;:{&#34;renditions&#34;:{&#34;(min-width: 768px) and (max-width: 979px)&#34;:&#34;-1_330&#34;,&#34;(min-width: 768px) and (max-width: 979px) and (-webkit-min-device-pixel-ratio: 2)&#34;:&#34;-1_660&#34;,&#34;(min-width: 1300px) and (max-width: 1920px) and (-webkit-min-device-pixel-ratio: 2)&#34;:&#34;-1_1200&#34;,&#34;(max-width: 767px) and (-webkit-min-device-pixel-ratio: 2)&#34;:&#34;-1_544&#34;,&#34;(max-width: 767px)&#34;:&#34;-1_272&#34;,&#34;(min-width: 1300px) and (max-width: 1920px)&#34;:&#34;-1_420&#34;,&#34;(min-width: 980px) and (max-width: 1299px) and (-webkit-min-device-pixel-ratio: 2)&#34;:&#34;-1_560&#34;,&#34;(min-width: 980px) and (max-width: 1299px)&#34;:&#34;-1_280&#34;,&#34;(min-width: 1921px)&#34;:&#34;-1_600&#34;},&#34;backgroundImage&#34;:false},&#34;Container_component_hero&#34;:{&#34;renditions&#34;:{&#34;(min-width: 768px) and (max-width: 979px)&#34;:&#34;-1_-1&#34;,&#34;(min-width: 768px) and (max-width: 979px) and (-webkit-min-device-pixel-ratio: 2)&#34;:&#34;-1_-1&#34;,&#34;(min-width: 1300px) and (max-width: 1920px) and (-webkit-min-device-pixel-ratio: 2)&#34;:&#34;-1_702&#34;,&#34;(max-width: 767px) and (-webkit-min-device-pixel-ratio: 2)&#34;:&#34;-1_-1&#34;,&#34;(max-width: 767px)&#34;:&#34;-1_-1&#34;,&#34;(min-width: 1300px) and (max-width: 1920px)&#34;:&#34;-1_351&#34;,&#34;(min-width: 980px) and (max-width: 1299px) and (-webkit-min-device-pixel-ratio: 2)&#34;:&#34;-1_640&#34;,&#34;(min-width: 980px) and (max-width: 1299px)&#34;:&#34;-1_320&#34;,&#34;(min-width: 1921px)&#34;:&#34;-1_351&#34;},&#34;backgroundImage&#34;:false},&#34;Container_component&#34;:{&#34;renditions&#34;:{&#34;(min-width: 768px) and (max-width: 979px)&#34;:&#34;-1_-1&#34;,&#34;(min-width: 768px) and (max-width: 979px) and (-webkit-min-device-pixel-ratio: 2)&#34;:&#34;-1_-1&#34;,&#34;(min-width: 1300px) and (max-width: 1920px) and (-webkit-min-device-pixel-ratio: 2)&#34;:&#34;-1_-1&#34;,&#34;(max-width: 767px) and (-webkit-min-device-pixel-ratio: 2)&#34;:&#34;-1_-1&#34;,&#34;(max-width: 767px)&#34;:&#34;-1_-1&#34;,&#34;(min-width: 1300px) and (max-width: 1920px)&#34;:&#34;-1_-1&#34;,&#34;(min-width: 980px) and (max-width: 1299px) and (-webkit-min-device-pixel-ratio: 2)&#34;:&#34;-1_-1&#34;,&#34;(min-width: 980px) and (max-width: 1299px)&#34;:&#34;-1_-1&#34;,&#34;(min-width: 1921px)&#34;:&#34;-1_-1&#34;},&#34;backgroundImage&#34;:false},&#34;Image_component-lightbox&#34;:{&#34;renditions&#34;:{&#34;(min-width: 768px) and (max-width: 979px)&#34;:&#34;-1_-1&#34;,&#34;(min-width: 768px) and (max-width: 979px) and (-webkit-min-device-pixel-ratio: 2)&#34;:&#34;-1_-1&#34;,&#34;(min-width: 1300px) and (max-width: 1920px) and (-webkit-min-device-pixel-ratio: 2)&#34;:&#34;-1_-1&#34;,&#34;(max-width: 767px) and (-webkit-min-device-pixel-ratio: 2)&#34;:&#34;-1_-1&#34;,&#34;(max-width: 767px)&#34;:&#34;-1_-1&#34;,&#34;(min-width: 1300px) and (max-width: 1920px)&#34;:&#34;-1_-1&#34;,&#34;(min-width: 980px) and (max-width: 1299px) and (-webkit-min-device-pixel-ratio: 2)&#34;:&#34;-1_-1&#34;,&#34;(min-width: 980px) and (max-width: 1299px)&#34;:&#34;-1_-1&#34;,&#34;(min-width: 1921px)&#34;:&#34;-1_-1&#34;},&#34;backgroundImage&#34;:false}}}"/>
        <link rel="stylesheet" href="/etc.clientlibs/developers/clientlibs/clientlib-responsive-style.min.16af0f34fb8554a922d5e5f3737c8aa0.css" type="text/css">
        <link rel="stylesheet" href="/etc.clientlibs/developers/clientlibs/clientlib-generic.min.f29a2b4f2a1bbd39034e5c82a55e2daf.css" type="text/css">
        <script src="/etc.clientlibs/clientlibs/granite/jquery.min.f65891607efbe75b84a8031849cec6c7.js"></script>
        <script src="/etc.clientlibs/clientlibs/granite/utils.min.fd64744866d6499535dd464d6da82678.js"></script>
        <script src="/etc.clientlibs/clientlibs/granite/jquery/granite.min.da45f476f6c3ee364516239ac10cd5f1.js"></script>
        <script src="/etc.clientlibs/foundation/clientlibs/jquery.min.dd9b395c741ce2784096e26619e14910.js"></script>
        <script src="/etc.clientlibs/sapdx/clientlibs/clientlib-handlebars.min.16a2d71aa7c87d0187a4faf3f6c82e52.js"></script>
        <script src="/etc.clientlibs/foundation/clientlibs/shared.min.6cd003256d877aa91c7c5632fd28d19d.js"></script>
        <script src="/etc.clientlibs/clientlibs/granite/jquery-ui.min.853d1707ce9dd94fe0d84aa6140b4cc0.js"></script>
        <script src="/etc.clientlibs/developers/clientlibs/clientlib-developers-global-usage/clientlib-developers-global-usage-codebase.min.08d9f1de8e74e608101d49b28b8b5425.js"></script>
        <script src="/etc.clientlibs/developers/clientlibs/clientlib-responsive-common.min.f2c5a54cc4ba7ff0744baf123e0b2491.js"></script>
        <script src="/etc.clientlibs/developers/clientlibs/clientlib-generic.min.81f53116886949d6b44b1da11284bc74.js"></script>
        <script src="/etc.clientlibs/sapdx/clientlibs/clientlib-react-specific.min.b19fe8745f72d390586beec0fbf33824.js"></script>
        <link rel="stylesheet" href="/etc.clientlibs/developers/clientlibs/clientlib-tutorial-github-prism.min.064dc0ee9c918aeacc8a874915ed3182.css" type="text/css">
        <script src="/etc.clientlibs/developers/clientlibs/clientlib-tutorial-github-prism.min.fa931b365a1fd3ff8972315465a40f23.js"></script>
        <script type="text/javascript">
            (function() {
                window.SAP = window.SAP || {};
                SAP.DTM = SAP.DTM || {};
                SAP.DTM.pageComponents = ["developers/components/page/homePage", "developers/components/modular/tutorial/tutorialCatalog", "sapdx/components/modular/nav/headerStandard", "nt:unstructured", "developers/components/modular/developerShortcuts", "developers/components/modular/responsive/responsiveVideo", "sapdx/components/modular/nav/footer", "developers/components/page/responsive/tutorialPage", "nt:file", "developers/components/modular/responsive/containerCarousel", "developers/components/modular/tutorial/nextSteps", "developers/components/page/tutorialCatalogPage", "wcm/foundation/components/responsivegrid", "nt:resource", "developers/components/modular/responsive/container", "developers/components/modular/responsive/image", "developers/components/modular/responsive/responsiveText", "developers/components/modular/responsive/tutorialPage", "sapdx/components/modular/countrySelector", "foundation/components/iparsys"];
                SAP.DTM.runMode = "prod";
            }
            )();
        </script>
        <script src="//assets.adobedtm.com/ccc66c06b30b/4e2aa6d7bbae/launch-82fd3e62f97c.min.js"></script>
        <style>
            #teconsent {
                display: none!important
            }

            #consent_blackbar {
                bottom: -15px;
                position: fixed;
                z-index: 1000000;
                width: 100%
            }

            #header {
                height: 64px;
                background-color: #000
            }

            #header.tier2 {
                background-color: #f4f4f4
            }

            #footer {
                background-color: #222
            }

            #footer.tier2 {
                background-color: #f4f4f4
            }

            [data-is-publish] [data-component=SecondaryNavigation] {
                position: static;
                min-height: 45px;
                width: 100%;
                z-index: 22
            }

            @media only screen and (min-width: 768px) {
                [data-is-publish] [data-component=SecondaryNavigation] {
                    min-height:84px
                }
            }

            .sectionUI2020 {
                min-height: 180px
            }

            .standardGrid3.is-lightbox .sectionUI2020 {
                min-height: 200px
            }

            .universalLayoutUI2020.horizontal {
                min-height: 300px
            }

            .universalLayoutUI2020.horizontal.one-box {
                min-height: 100px
            }

            .universalLayoutUI2020.horizontal.two-boxes,.universalLayoutUI2020.vertical {
                min-height: 200px
            }

            .standardGrid3.is-lightbox .universalLayoutUI2020 {
                min-height: 50px
            }

            .heroUniversalUI2020.preview-large,.heroUniversalUI2020.preview-medium {
                min-height: 238px
            }

            .heroUniversalUI2020.preview-small {
                height: 135px
            }

            @media only screen and (min-width: 980px) {
                .heroUniversalUI2020.preview-small {
                    height:146px
                }
            }

            html:not(.aem-AuthorLayer-Preview) #header.cq-Editable-dom {
                height: 280px;
                background-color: #fff
            }

            .storyContainer {
                background: #222;
                color: #fff;
                padding-top: 5.25rem
            }

            .customer-reference-standard .carousel-holder .carousel-mask .carousel-slider {
                display: flex
            }

            .customer-reference-standard .carousel-holder .carousel-mask .carousel-slider .max-divider {
                min-width: 3.25rem
            }

            .customer-reference-standard .item-content .navbar-item-icon-link:after {
                display: none
            }

            .customer-reference-standard .item-content .navbar-item-icon-link .navbar-item-icon {
                width: 140px;
                height: 86px
            }

            .customer-reference-standard .item-content .navbar-item-icon-link .navbar-item-icon .svg-image {
                max-width: 140px;
                max-height: 90%;
                filter: grayscale(100%)
            }

            .customer-reference-standard .arrows {
                display: none
            }

            @media only screen and (max-width: 767px) {
                .navigation-icon-bar-standard {
                    min-height:180px
                }
            }

            .hidden-chat-button {
                display: none
            }

            .event-includer-visible {
                min-height: 75px
            }

            @media only screen and (max-width: 767px) {
                .event-includer-visible {
                    min-height:100px
                }
            }

            .flexible-columns .flexible-columns__left-column {
                margin-left: 10px
            }

            .flexible-columns .flexible-columns__right-column {
                margin-right: 10px
            }

            @media only screen and (max-width: 1023px) {
                .flexible-columns .flexible-columns__left-column {
                    margin-left:0
                }

                .flexible-columns .flexible-columns__right-column {
                    margin-right: 0
                }
            }

            .developerShortcuts {
                height: 70px
            }

            .tutorial-header .title {
                margin-bottom: 20px
            }

            @media only screen and (max-width: 1023px) {
                .tutorial-header .steps-wrapper_scroll {
                    margin-bottom:30px
                }
            }

            .tutorialPageTitle {
                display: flex;
                margin-bottom: 10px;
                justify-content: space-between
            }

            .tutorialPageTitle h1 {
                color: #1f1f1f;
                font-style: normal;
                font-weight: 400;
                font-size: 2.5rem;
                line-height: 2.875rem
            }

            .tutorialSummary .info img {
                width: 45px;
                height: 45px
            }

            .tutorialSummary .icon-key:before {
                min-width: 20px;
                min-height: 22px
            }

            [data-resource-holder] {
                display: none
            }

            @media only screen and (max-width: 1023px) {
                .tutorialSummary .body {
                    min-height:215px
                }

                .tutorialSummary .title {
                    min-height: 72px
                }

                .tutorialBody .done-button {
                    min-height: 77px
                }

                .tutorialDescription {
                    padding: 40px 20px 20px
                }

                .tutorialDescription .copied-content {
                    min-height: 361px
                }

                .tutorialDescription .textAndIcon {
                    min-height: 69px
                }

                .tutorialDescription .tutorial-miniNavigator {
                    margin-bottom: 0
                }

                .tutorialDescription .tutorial-contents {
                    min-height: 256px
                }
            }
        </style>
        <script defer="defer" src="/etc.clientlibs/sapdx/front-layer/dist/resources/developers-responsive/runtime.03f1d1a9edb12a3799e7.js"></script>
        <script defer="defer" src="/etc.clientlibs/sapdx/front-layer/dist/resources/developers-responsive/default.6f0d7f7a9b49a3d7ef3d.js"></script>
        <script defer="defer" src="/etc.clientlibs/sapdx/front-layer/dist/resources/developers-responsive/critical.630f89abfd865edd3a04.js"></script>
        <script defer="defer" src="/etc.clientlibs/sapdx/front-layer/dist/resources/developers-responsive/8508.26ad809d92c11dc4fba0.js"></script>
        <script defer="defer" src="/etc.clientlibs/sapdx/front-layer/dist/resources/developers-responsive/5306.4abaf120e24302f1e47b.js"></script>
        <script defer="defer" src="/etc.clientlibs/sapdx/front-layer/dist/resources/developers-responsive/developers-responsive.a20a05da32d2b1605859.js"></script>
        <link href="/etc.clientlibs/sapdx/front-layer/dist/resources/developers-responsive/default.141634ed0ecca33eaa3c.css" rel="stylesheet"/>
        <link href="/etc.clientlibs/sapdx/front-layer/dist/resources/developers-responsive/developers-responsive.0bee8b9d7f2c802de70c.css" rel="stylesheet"/>
        <script>
            window.schema_highlighter = {
                outputCache: true,
                key: "325UM-NQRHZ-P7T97-M5SY8",
                accountId: "Acronym/Developers"
            }
        </script>
        <script async src="https://cdn.schemaapp.com/javascript/highlight.js"></script>
    </head>
    <body class="is-publish-true tutorialPage" data-enable-livefyre="false">
        <noscript>
            <div class="nojs">Javascript must be enabled for the correct page display</div>
        </noscript>
        <div id="page">
            <div id="idsConfig" class="hidden" data-ids-sp-name="sapdxdevs" data-ids-cookie-loggedout-value="xxxxxx"></div>
            <div id="trusteConfig" class="hidden" data-eu-countries="no,de,be,fi,pt,bg,dk,lt,lu,hr,lv,fr,hu,se,si,sk,gb,ie,ee,mt,is,it,gr,es,at,cy,cz,pl,li,ro,nl"></div>
            <b class="accessibility">
                <a href="#main" tabindex="0" accesskey="S">Skip to Content</a>
            </b>
            <header id="header" class="tier2">
                <div data-menu-host="https://www.sap.com"></div>
                <div class="container"></div>
                <div class="section">
                    <div class="new"></div>
                </div>
                <div class="iparys_inherited">
                    <div class="parHeader iparsys parsys">
                        <div class="headerStandard genericComponent parbase section">
                            <div data-component="HeaderStandard" data-model="/bin/sapdxc/cache/header/content/developers/website/languages/en/_jcr_content/parHeader/headerstandard.model.json" data-show-in-navigation data-country-selector-path="/bin/sapdxc/cache/header/content/developers/website/languages/en/tutorials/build-apps-workflow-trigger/_jcr_content/parHeader/headerstandard.model.countryselector.json" data-language-selector-path="/bin/sapdxc/cache/header/content/developers/website/languages/en/tutorials/build-apps-workflow-trigger/_jcr_content/parHeader/headerstandard.model.languageselector.json"></div>
                        </div>
                    </div>
                </div>
                <div class="currentpage-context hidden">
                    <div class="footer-current-context-page-data" data-mailto-share-link="https://developers.sap.com/tutorials/build-apps-workflow-trigger.html"></div>
                </div>
            </header>
            <div id="main" class="main">
                <div class="container">
                    <div class="standard-layout-wrapper">
                        <div>
                            <div class="aem-Grid aem-Grid--12 aem-Grid--default--12">
                                <div class="responsivegrid aem-GridColumn aem-GridColumn--default--12">
                                    <div class="aem-Grid aem-Grid--12 aem-Grid--default--12">
                                        <div class="tutorialPage responsivegrid aem-GridColumn aem-GridColumn--default--12">
                                            <div data-model="/content/developers/website/languages/en/tutorials/build-apps-workflow-trigger/jcr:content/par/par1/contentParsys.model.json" data-component="TutorialPage">
                                                <nav aria-label="Breadcrumb" class="NavigationPath__navigation--DMGIy">
                                                    <div class="NavigationPath__navigationPath--ugfpT">
                                                        <div>
                                                            <a class="NavigationPath__navigationItem--gpRXz" href="/tutorial-navigator.html">Tutorial Navigator</a>
                                                        </div>
                                                        <div class="Breadcrumb__breadcrumbTitle--1gFeX">
                                                            <a href="">Create SAP Build App to Trigger Workflow</a>
                                                        </div>
                                                    </div>
                                                </nav>
                                                <nav class="ButtonBar__buttonbar--SJ1XH ButtonBar__hidden--iXeZn">
                                                    <div class="ButtonBar__buttonbarNext--x3qsX"></div>
                                                </nav>
                                                <section aria-label="Main section" class="TutorialPage__tutorialPageWrapper--Dp+Iv">
                                                    <div class="TutorialContent__tutorialContentWrapper--QSNSa">
                                                        <div>
                                                            <div class="tutorialPageTitle">
                                                                <h1 class="fontRegular">Create SAP Build App to Trigger Workflow</h1>
                                                            </div>
                                                            <div class="Header__info--i+hCi">
                                                                <div class="Header__proficiency--vBvRF proficiency d64acece-d95f-47a5-9e70-71c487db6c5a">
                                                                    <svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                                                                        <path d="M12.7941 13.3956L4.26672 9.61212L12.3286 5.82861L20.856 9.61212L12.7941 13.3956Z" fill="#008FD3"></path>
                                                                        <path opacity="0.4" d="M8.2118 11.6896L6.07382 10.7269L15.5018 6.30371L17.6336 7.26634L8.2118 11.6896Z" fill="#F0AB00"></path>
                                                                        <path opacity="0.7" d="M10.2699 12.7741L8.138 11.8114L17.5598 7.38818L19.6978 8.35082L10.2699 12.7741Z" fill="#F0AB00"></path>
                                                                        <path d="M12.4939 13.7125L10.3621 12.7499L19.7839 8.32666L21.9219 9.29538L12.4939 13.7125Z" fill="#F0AB00"></path>
                                                                        <path d="M12.5 5.99919L20.7211 9.59383L12.5 13.1885L4.27888 9.59383L12.5 5.99919ZM12.5 5L2 9.59383L12.5 14.1877L23 9.59383L12.5 5Z" fill="black"></path>
                                                                        <path d="M12.5303 18.245C12.5058 18.245 12.4751 18.245 12.4506 18.245C9.39988 18.2268 7.11488 17.1179 6.14084 16.6488L5.88354 16.5208V10.8364H6.80245V15.9481C7.83162 16.4355 9.85933 17.3129 12.4568 17.3311C12.4813 17.3311 12.5058 17.3311 12.5303 17.3311C15.189 17.3311 17.2351 16.4416 18.2826 15.9481V10.9034H19.2015V16.5208L18.9442 16.6488C17.9518 17.1301 15.6423 18.245 12.5303 18.245Z" fill="black"></path>
                                                                        <path d="M17.303 19.4516L16.3167 20V11.5434L12.3899 9.42928L13.4313 8.92969L17.303 10.9037V19.4516Z" fill="black"></path>
                                                                    </svg>
                                                                    Beginner
                                                                </div>
                                                                <div class="Header__timeToComplete--TbRqU time-to-complete">
                                                                    <svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                                                                        <g clip-path="url(#clip)">
                                                                            <path d="M19 11.9636V12C19 13.2601 18.6649 14.4402 18.0895 15.4599C17.0114 17.3538 15.0812 18.6941 12.8231 18.9563H11.1842C8.92612 18.6941 6.98855 17.3538 5.91779 15.4599C5.33507 14.4402 5 13.2601 5 12H12V5C14.5786 5 16.8293 6.39854 18.0458 8.47451C18.6504 9.49428 18.9927 10.6889 19 11.9636Z" fill="#E35500"></path>
                                                                            <path opacity="0.4" d="M19.0004 11.9636H12.0004V8.46729H18.0462C18.6507 9.49434 18.9931 10.6889 19.0004 11.9636Z" fill="#F0AB00"></path>
                                                                            <path opacity="0.7" d="M19 11.9634V11.9998C19 13.2599 18.6649 14.44 18.0895 15.4597H5.91051C5.33507 14.44 5 13.2599 5 11.9998H12V11.9634H19Z" fill="#F0AB00"></path>
                                                                            <path d="M18.0898 15.46C17.0117 17.3538 15.0814 18.6941 12.8234 18.9563H11.1845C8.92639 18.6941 6.98882 17.3538 5.91806 15.46H18.0898Z" fill="#F0AB00"></path>
                                                                            <path d="M19 11.9636V12C19 13.2601 18.6649 14.4402 18.0895 15.4599C17.0114 17.3538 15.0812 18.6941 12.8231 18.9563H11.1842C8.92612 18.6941 6.98855 17.3538 5.91779 15.4599C5.33507 14.4402 5 13.2601 5 12H12V5C14.5786 5 16.8293 6.39854 18.0458 8.47451C18.6504 9.49428 18.9927 10.6889 19 11.9636Z" fill="#E35500"></path>
                                                                            <path opacity="0.4" d="M19.0004 11.9636H12.0004V8.46729H18.0462C18.6507 9.49434 18.9931 10.6889 19.0004 11.9636Z" fill="#F0AB00"></path>
                                                                            <path opacity="0.7" d="M19 11.9634V11.9998C19 13.2599 18.6649 14.44 18.0895 15.4597H5.91051C5.33507 14.44 5 13.2599 5 11.9998H12V11.9634H19Z" fill="#F0AB00"></path>
                                                                            <path d="M18.0898 15.46C17.0117 17.3538 15.0814 18.6941 12.8234 18.9563H11.1845C8.92639 18.6941 6.98882 17.3538 5.91806 15.46H18.0898Z" fill="#F0AB00"></path>
                                                                            <path d="M12 6.09261C15.256 6.09261 17.9074 8.74402 17.9074 12C17.9074 15.256 15.256 17.9074 12 17.9074C8.74402 17.9074 6.09261 15.256 6.09261 12C6.09261 8.74402 8.74402 6.09261 12 6.09261ZM12 5C8.13215 5 5 8.13215 5 12C5 15.8678 8.13215 19 12 19C15.8678 19 19 15.8678 19 12C19 8.13215 15.8678 5 12 5Z" fill="#1F1F1F"></path>
                                                                        </g>
                                                                        <defs>
                                                                            <clipPath id="clip">
                                                                                <rect width="14" height="14" fill="white" transform="translate(5 5)"></rect>
                                                                            </clipPath>
                                                                        </defs>
                                                                    </svg>
                                                                    25 min.
                                                                </div>
                                                                <div class="Header__tagLinkList--1OXYn">
                                                                    <svg width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
                                                                        <path d="M10.1655 14.0734L10.1654 14.0733C9.86914 14.3544 9.50572 14.505 9.09703 14.505C8.68517 14.505 8.31852 14.3555 8.02707 14.064L8.02682 14.0638L2.3658 8.39483C2.10562 8.14061 1.90117 7.81242 1.74065 7.43194L1.73803 7.42573L1.73807 7.42571C1.58334 7.04482 1.495 6.67043 1.495 6.30891V3.01386C1.495 2.60041 1.65208 2.23573 1.9439 1.9439C2.23573 1.65208 2.60041 1.495 3.01386 1.495H6.30891C6.67264 1.495 7.04818 1.58704 7.42883 1.74726C7.81089 1.90284 8.14147 2.10452 8.40065 2.3637L14.0638 8.0189L14.0734 8.02854L14.0733 8.02867C14.3544 8.32492 14.505 8.68834 14.505 9.09703C14.505 9.50872 14.3556 9.87524 14.0644 10.1666C14.0643 10.1667 14.0641 10.1669 14.064 10.167M10.1655 14.0734L14.064 10.167M10.1655 14.0734L10.1753 14.0637L14.064 10.167M10.1655 14.0734L14.064 10.167M4.88571 4.17408L4.88558 4.1742L4.89523 4.1836C4.99833 4.28399 5.04351 4.39116 5.04351 4.53465C5.04351 4.6785 4.99788 4.79092 4.89044 4.89836C4.79112 4.99767 4.68253 5.04351 4.53465 5.04351C4.38874 5.04351 4.27606 4.99866 4.171 4.8983C4.07064 4.79324 4.02579 4.68057 4.02579 4.53465C4.02579 4.38678 4.07164 4.27818 4.17095 4.17887C4.27839 4.07143 4.39081 4.02579 4.53465 4.02579C4.67814 4.02579 4.78531 4.07097 4.88571 4.17408Z" fill="#4E5459" stroke="black" stroke-width="1.01"></path>
                                                                        <mask id="mask0" style="mask-type:alpha" maskUnits="userSpaceOnUse" x="2" y="2" width="12" height="12">
                                                                            <path d="M3.46031 3.46823L3.81386 3.82178L3.46031 3.46823C3.16981 3.75873 3.02079 4.1241 3.02079 4.53465C3.02079 4.94493 3.16942 5.31031 3.45563 5.60425L3.4555 5.60438L3.46505 5.61368C3.759 5.89989 4.12438 6.04851 4.53465 6.04851C4.94521 6.04851 5.31058 5.8995 5.60108 5.609C5.89404 5.31604 6.04851 4.9492 6.04851 4.53465C6.04851 4.12198 5.89524 3.7569 5.6011 3.4682C5.3124 3.17407 4.94732 3.02079 4.53465 3.02079C4.12011 3.02079 3.75327 3.17527 3.46031 3.46823ZM13.3534 9.45635L13.353 9.45671L9.46933 13.3483C9.35421 13.4559 9.23707 13.5 9.09703 13.5C8.94785 13.5 8.83798 13.4536 8.73771 13.3534L3.07459 7.68234L3.07463 7.6823L3.0696 7.67741C2.92963 7.54112 2.79185 7.33727 2.66792 7.04437C2.54881 6.75032 2.5 6.50725 2.5 6.30891V3.01386C2.5 2.87676 2.54415 2.76494 2.65454 2.65454C2.76494 2.54414 2.87676 2.5 3.01386 2.5H6.30891C6.50477 2.5 6.74667 2.55025 7.04129 2.67454L7.04128 2.67458L7.04746 2.67709C7.34044 2.79612 7.54799 2.93232 7.69001 3.07435L7.69026 3.07459L13.3483 8.72469C13.4559 8.83982 13.5 8.95697 13.5 9.09703C13.5 9.24621 13.4536 9.35609 13.3534 9.45635Z" fill="white" stroke="black"></path>
                                                                        </mask>
                                                                        <g mask="url(#mask0)">
                                                                            <rect x="-3.4751" y="7.75977" width="22.6341" height="13.9287" transform="rotate(-45 -3.4751 7.75977)" fill="#008FD3"></rect>
                                                                            <rect opacity="0.7" x="1.44971" y="12.6846" width="22.6341" height="3.48217" transform="rotate(-45 1.44971 12.6846)" fill="#F0AB00"></rect>
                                                                            <rect opacity="0.4" x="-1.01318" y="10.2222" width="22.6341" height="3.48217" transform="rotate(-45 -1.01318 10.2222)" fill="#F0AB00"></rect>
                                                                            <rect x="3.91162" y="15.1465" width="22.6341" height="3.48217" transform="rotate(-45 3.91162 15.1465)" fill="#F0AB00"></rect>
                                                                        </g>
                                                                    </svg>
                                                                    <div class="Header__tagLinkListContainer--9c1KP">
                                                                        <a href="/tutorial-navigator.html?tag=software-product:technology-platform/sap-build" class="Header__tagLink--4IJSq">SAP Build</a>
                                                                        , <a href="/tutorial-navigator.html?tag=software-product:technology-platform/sap-build/sap-build-process-automation" class="Header__tagLink--4IJSq">SAP Build Process Automation</a>
                                                                        , <a href="/tutorial-navigator.html?tag=tutorial:experience/beginner" class="Header__tagLink--4IJSq">Beginner</a>
                                                                        , <a href="/tutorial-navigator.html?tag=type:tutorial" class="Header__tagLink--4IJSq">Tutorial</a>
                                                                        , <a href="/tutorial-navigator.html?tag=software-product:technology-platform/sap-business-technology-platform/sap-business-technology-platform" class="Header__tagLink--4IJSq">SAP Business Technology Platform</a>
                                                                        , <a href="/tutorial-navigator.html?tag=software-product:technology-platform/sap-build/sap-build-apps-enterprise-edition" class="Header__tagLink--4IJSq">SAP Build Apps, enterprise edition</a>
                                                                    </div>
                                                                </div>
                                                            </div>
                                                            <div class="Header__headerDescription--cstWX">Trigger a workflow created in SAP Build Process Automation from an app created with SAP build Apps.</div>
                                                            <div class="you-will-learn">
                                                                You will learn
                                                                <ul>
                                                                    <li>How to create a simple UI</li>
                                                                    <li>How to create a form</li>
                                                                    <li>How to stylize your UI</li>
                                                                    <li>How to trigger from your app a workflow in SAP Build Process Automation</li>
                                                                </ul>
                                                            </div>
                                                            <div class="Header__contributorsSection--6x4f6">
                                                                <div class="Header__autorSection--mOlaB Header__section--ALPig">
                                                                    <a href="https://github.com/thecodester" title="Daniel Wroblewski" class="Header__owner--3EP+z">
                                                                        <img src="https://avatars.githubusercontent.com/u/11659786?v=4" alt="thecodester" class="Header__ownerAvatar--UGjWd"/>
                                                                        <span>Daniel Wroblewski</span>
                                                                    </a>
                                                                    <span class="Header__creationTime--0FWBe">March 5, 2023</span>
                                                                </div>
                                                                <div class="Header__creatorsSection--xEnD3 Header__section--ALPig">
                                                                    <div class="Header__creator--SxoJy Header__section--ALPig">
                                                                        <span class="Header__createdBy--fQnSC Header__creatorInfo--Xd75I">Created by</span>
                                                                        <div class="Header__creatorInfo--Xd75I">
                                                                            <a href="https://github.com/thecodester" title="Daniel Wroblewski">
                                                                                <img src="https://avatars.githubusercontent.com/u/11659786?v=4" alt="thecodester" class="Header__creatorImage--pWNDz"/>
                                                                            </a>
                                                                        </div>
                                                                        <span class="Header__creatorInfo--Xd75I">January 25, 2023</span>
                                                                    </div>
                                                                    <div class="Header__contributorsWrapper--CLGRK Header__section--ALPig">
                                                                        <span class="Header__contributorsTitle--5aaPP">Contributors</span>
                                                                        <div>
                                                                            <a class="Header__colabLink--ROAcF" href="https://github.com/thecodester" title="Daniel Wroblewski" target="_blank" rel="noopener noreferrer">
                                                                                <img class="Header__colabLinkImg--j7YSj" src="https://avatars.githubusercontent.com/u/11659786?v=4" alt="thecodester"/>
                                                                            </a>
                                                                        </div>
                                                                    </div>
                                                                </div>
                                                            </div>
                                                            <div class="Header__prerequisites--jv0hU">
                                                                <h2 class="Header__title--WIuME">Prerequisites</h2>
                                                                <ul>
                                                                    <li>You have set up SAP Build App and have entered the lobby.</li>
                                                                    <li>
                                                                        You have set up SAP Process Automation, and created the process described in the tutorial group <a href="https://developers.sap.com/group.sap-build-apps-process-trigger-enable.html" target="_blank" data-title="Create a Sales Order Process and Enable Triggering Via API">Create a Sales Order Process and Enable Triggering Via API</a>
                                                                        .
                                                                    </li>
                                                                    <li>
                                                                        You will have to know the <code>definitionId</code>
                                                                        for the process you created.
                                                                    </li>
                                                                    <li>
                                                                        You have set up the destination to SAP Build Process Automation, as described in <a href="https://developers.sap.com/tutorials/spa-create-service-instance-destination.html" target="_blank" data-title="Create Destination to Trigger Process from any Service">Create Destination to Trigger Process from any Service</a>
                                                                        .
                                                                    </li>
                                                                    <li>You will have to know the name of the destination.</li>
                                                                </ul>
                                                            </div>
                                                            <div class="tutorialBody">
                                                                <p>This tutorial shows you how to use SAP Build Apps to create and stylize a simple, one-page app that triggers an SAP Build Process Automation workflow.</p>
                                                                <p>Specifically, the app lets the user enter sales order details and then send these to a process for approval, before the sales would be automatically created in S/4HANA Cloud.</p>
                                                                <p>Your app will look something like this:</p>
                                                                <img src="/tutorials/build-apps-workflow-trigger/_jcr_content.github-proxy.1678009502.file/page1-goal.png" alt="Your app"/>
                                                                <p></p>
                                                                <blockquote>
                                                                    <p>
                                                                        <strong>Before You Begin:</strong>
                                                                        You will need:
                                                                    </p>
                                                                    <ul>
                                                                        <li>
                                                                            <p>
                                                                                The name of the SAP BTP destination to your SAP Build Process Automation instance (for workshops, this will be done for you). The destination <strong>MUST</strong>
                                                                                be configured with the URL of the entire path of the SAP Build Process Automation <a href="https://api.sap.com/api/SPA_Workflow_Runtime/resource" target="_blank" data-title="Workflow Instances API">Workflow Instances API</a>
                                                                                .
                                                                            </p>
                                                                        </li>
                                                                        <li>
                                                                            <p>
                                                                                The <code>definitionId</code>
                                                                                for your specific workflow, which you can find within your trigger in SAP Build Process Automation project. You can get this by going to your triggers in the Deployed version of your project, and clicking <strong>View</strong>
                                                                                .
                                                                            </p>
                                                                        </li>
                                                                    </ul>
                                                                    <p>
                                                                        <img src="/tutorials/build-apps-workflow-trigger/_jcr_content.github-proxy.1678009502.file/definitionId.png" alt="Definition ID"/>
                                                                    </p>
                                                                </blockquote>
                                                            </div>
                                                        </div>
                                                        <div class="Body__body--JFi1e">
                                                            <div class="Options__options--J1ltZ">
                                                                <button class="Options__button--Uizy6">Open all</button>
                                                                <button class="Options__button--Uizy6">Close all</button>
                                                            </div>
                                                            <ul class="Accordion__list--MnHWm">
                                                                <li id="bce79e08-36cb-45eb-8dbe-a83ae0a0ff8c" class="Accordion__item--DNzPY">
                                                                    <div class="Expander__expander--4DOyC">
                                                                        <div class="Top__top--kjtjD">
                                                                            <div class="Top__type--CI8yu">
                                                                                <span class="Status__status--ucVFH false">
                                                                                    <svg width="20" height="20" viewBox="0 0 20 20" fill="none" xmlns="http://www.w3.org/2000/svg">
                                                                                        <circle cx="10" cy="10" r="9.5" fill="#EAEBEE" stroke="#B1B1B1"></circle>
                                                                                    </svg>
                                                                                </span>
                                                                                <span class="Top__title--BIOWY">Step 1</span>
                                                                            </div>
                                                                            <button class="ExpanderButton__expanderButton--2JY9n" title="Collapse content" aria-label="Toggle accordion">
                                                                                <svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                                                                                    <path fill-rule="evenodd" clip-rule="evenodd" d="M2.40474 12.0001H21.4744H2.40474Z" fill="#003283"></path>
                                                                                    <path d="M2.40474 12.0001H21.4744" stroke="#085CAF" stroke-width="3" stroke-linecap="round" stroke-linejoin="round"></path>
                                                                                    <path fill-rule="evenodd" clip-rule="evenodd" d="M11.9401 2.40767L11.9401 21.5942L11.9401 2.40767Z" fill="#003283"></path>
                                                                                    <path d="M11.9401 2.40767L11.9401 21.5942" stroke="#085CAF" stroke-width="3" stroke-linecap="round" stroke-linejoin="round"></path>
                                                                                </svg>
                                                                            </button>
                                                                        </div>
                                                                        <div class="Header__bottom--mSn+X">
                                                                            <div>
                                                                                <button class="Header__title--W0rcU">
                                                                                    <span class="Header__url--+cB+Z Header__linked--TcvJ0">Create a new app project</span>
                                                                                </button>
                                                                                <div class="Header__wrapper--XNMcL"></div>
                                                                            </div>
                                                                        </div>
                                                                        <div class="Expander__wrapper--GK6+l">
                                                                            <div class="Expander__hide--Q-ULJ">
                                                                                <div class="Expander__separator--dU1cP"></div>
                                                                                <div>
                                                                                    <div>
                                                                                        <div class="tutorialBody">
                                                                                            <p>
                                                                                                Go to the SAP Build lobby, and click <strong>Create</strong>
                                                                                                .
                                                                                            </p>
                                                                                            <div class="img-zoom img-zoom__hidden">
                                                                                                <div class="enlarge-icon">
                                                                                                    <svg width="40px" height="40px" viewBox="0 0 40 40" version="1.1" xmlns="http://www.w3.org/2000/svg">
                                                                                                        <g id="Atoms/Icons/Enlarge" stroke="none" stroke-width="1" fill="none" fill-rule="evenodd">
                                                                                                            <rect id="Rectangle" fill="#E9E9E9" opacity="0.8" x="0" y="0" width="40" height="40" rx="4"></rect>
                                                                                                            <g id="enlarge-icon" transform="translate(8.000000, 8.000000)" fill="#000000" fill-rule="nonzero">
                                                                                                                <polygon id="Path" points="24 0 14.25 0 18 3.75 13.5 8.25 15.75 10.5 20.25 6 24 9.75"></polygon>
                                                                                                                <polygon id="Path" points="24 24 24 14.25 20.25 18 15.75 13.5 13.5 15.75 18 20.25 14.25 24"></polygon>
                                                                                                                <polygon id="Path" points="0 24 9.75 24 6 20.25 10.5 15.75 8.25 13.5 3.75 18 0 14.25"></polygon>
                                                                                                                <polygon id="Path" points="0 0 0 9.75 3.75 6 8.25 10.5 10.5 8.25 6 3.75 9.75 0"></polygon>
                                                                                                            </g>
                                                                                                        </g>
                                                                                                    </svg>
                                                                                                </div>
                                                                                                <img src="/tutorials/build-apps-workflow-trigger/_jcr_content.github-proxy.1678009502.file/new-project-create.png" alt="Create project"/>
                                                                                            </div>
                                                                                            <p>
                                                                                                Select <strong>Build an Application</strong>
                                                                                                .
                                                                                            </p>
                                                                                            <div class="img-zoom img-zoom__hidden">
                                                                                                <div class="enlarge-icon">
                                                                                                    <svg width="40px" height="40px" viewBox="0 0 40 40" version="1.1" xmlns="http://www.w3.org/2000/svg">
                                                                                                        <g id="Atoms/Icons/Enlarge" stroke="none" stroke-width="1" fill="none" fill-rule="evenodd">
                                                                                                            <rect id="Rectangle" fill="#E9E9E9" opacity="0.8" x="0" y="0" width="40" height="40" rx="4"></rect>
                                                                                                            <g id="enlarge-icon" transform="translate(8.000000, 8.000000)" fill="#000000" fill-rule="nonzero">
                                                                                                                <polygon id="Path" points="24 0 14.25 0 18 3.75 13.5 8.25 15.75 10.5 20.25 6 24 9.75"></polygon>
                                                                                                                <polygon id="Path" points="24 24 24 14.25 20.25 18 15.75 13.5 13.5 15.75 18 20.25 14.25 24"></polygon>
                                                                                                                <polygon id="Path" points="0 24 9.75 24 6 20.25 10.5 15.75 8.25 13.5 3.75 18 0 14.25"></polygon>
                                                                                                                <polygon id="Path" points="0 0 0 9.75 3.75 6 8.25 10.5 10.5 8.25 6 3.75 9.75 0"></polygon>
                                                                                                            </g>
                                                                                                        </g>
                                                                                                    </svg>
                                                                                                </div>
                                                                                                <img src="/tutorials/build-apps-workflow-trigger/_jcr_content.github-proxy.1678009502.file/new-project-appgyver.png" alt="Build an application"/>
                                                                                            </div>
                                                                                            <p>
                                                                                                Select <strong>Web &amp;Mobile Application</strong>
                                                                                                .
                                                                                            </p>
                                                                                            <div class="img-zoom img-zoom__hidden">
                                                                                                <div class="enlarge-icon">
                                                                                                    <svg width="40px" height="40px" viewBox="0 0 40 40" version="1.1" xmlns="http://www.w3.org/2000/svg">
                                                                                                        <g id="Atoms/Icons/Enlarge" stroke="none" stroke-width="1" fill="none" fill-rule="evenodd">
                                                                                                            <rect id="Rectangle" fill="#E9E9E9" opacity="0.8" x="0" y="0" width="40" height="40" rx="4"></rect>
                                                                                                            <g id="enlarge-icon" transform="translate(8.000000, 8.000000)" fill="#000000" fill-rule="nonzero">
                                                                                                                <polygon id="Path" points="24 0 14.25 0 18 3.75 13.5 8.25 15.75 10.5 20.25 6 24 9.75"></polygon>
                                                                                                                <polygon id="Path" points="24 24 24 14.25 20.25 18 15.75 13.5 13.5 15.75 18 20.25 14.25 24"></polygon>
                                                                                                                <polygon id="Path" points="0 24 9.75 24 6 20.25 10.5 15.75 8.25 13.5 3.75 18 0 14.25"></polygon>
                                                                                                                <polygon id="Path" points="0 0 0 9.75 3.75 6 8.25 10.5 10.5 8.25 6 3.75 9.75 0"></polygon>
                                                                                                            </g>
                                                                                                        </g>
                                                                                                    </svg>
                                                                                                </div>
                                                                                                <img src="/tutorials/build-apps-workflow-trigger/_jcr_content.github-proxy.1678009502.file/new-project-web-project.png" alt="Select project type"/>
                                                                                            </div>
                                                                                            <p>
                                                                                                For the project name, enter <code>Sales Order Trigger</code>
                                                                                                , then click <strong>Create</strong>
                                                                                                .
                                                                                            </p>
                                                                                            <div class="img-zoom img-zoom__hidden">
                                                                                                <div class="enlarge-icon">
                                                                                                    <svg width="40px" height="40px" viewBox="0 0 40 40" version="1.1" xmlns="http://www.w3.org/2000/svg">
                                                                                                        <g id="Atoms/Icons/Enlarge" stroke="none" stroke-width="1" fill="none" fill-rule="evenodd">
                                                                                                            <rect id="Rectangle" fill="#E9E9E9" opacity="0.8" x="0" y="0" width="40" height="40" rx="4"></rect>
                                                                                                            <g id="enlarge-icon" transform="translate(8.000000, 8.000000)" fill="#000000" fill-rule="nonzero">
                                                                                                                <polygon id="Path" points="24 0 14.25 0 18 3.75 13.5 8.25 15.75 10.5 20.25 6 24 9.75"></polygon>
                                                                                                                <polygon id="Path" points="24 24 24 14.25 20.25 18 15.75 13.5 13.5 15.75 18 20.25 14.25 24"></polygon>
                                                                                                                <polygon id="Path" points="0 24 9.75 24 6 20.25 10.5 15.75 8.25 13.5 3.75 18 0 14.25"></polygon>
                                                                                                                <polygon id="Path" points="0 0 0 9.75 3.75 6 8.25 10.5 10.5 8.25 6 3.75 9.75 0"></polygon>
                                                                                                            </g>
                                                                                                        </g>
                                                                                                    </svg>
                                                                                                </div>
                                                                                                <img src="/tutorials/build-apps-workflow-trigger/_jcr_content.github-proxy.1678009502.file/new-project-name.png" alt="Name project"/>
                                                                                            </div>
                                                                                        </div>
                                                                                        <div class="SubmitButton__root--QWQTU">
                                                                                            <span>
                                                                                                <a href="/bin/fiji/es/login.sapdxdevs.html" title="Log in">Log in</a>
                                                                                                to complete tutorial
                                                                                            </span>
                                                                                            <button disabled="" class="SubmitButton__button--I7eWM SubmitButton__disabled--V-NkW">Done</button>
                                                                                        </div>
                                                                                    </div>
                                                                                </div>
                                                                            </div>
                                                                        </div>
                                                                    </div>
                                                                </li>
                                                                <li id="92282e2c-3ad0-4796-9899-40e4ec2fe8eb" class="Accordion__item--DNzPY">
                                                                    <div class="Expander__expander--4DOyC">
                                                                        <div class="Top__top--kjtjD">
                                                                            <div class="Top__type--CI8yu">
                                                                                <span class="Status__status--ucVFH Top__chained--TywwF">
                                                                                    <svg width="20" height="20" viewBox="0 0 20 20" fill="none" xmlns="http://www.w3.org/2000/svg">
                                                                                        <circle cx="10" cy="10" r="9.5" fill="#EAEBEE" stroke="#B1B1B1"></circle>
                                                                                    </svg>
                                                                                </span>
                                                                                <span class="Top__title--BIOWY">Step 2</span>
                                                                            </div>
                                                                            <button class="ExpanderButton__expanderButton--2JY9n" title="Collapse content" aria-label="Toggle accordion">
                                                                                <svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                                                                                    <path fill-rule="evenodd" clip-rule="evenodd" d="M2.40474 12.0001H21.4744H2.40474Z" fill="#003283"></path>
                                                                                    <path d="M2.40474 12.0001H21.4744" stroke="#085CAF" stroke-width="3" stroke-linecap="round" stroke-linejoin="round"></path>
                                                                                    <path fill-rule="evenodd" clip-rule="evenodd" d="M11.9401 2.40767L11.9401 21.5942L11.9401 2.40767Z" fill="#003283"></path>
                                                                                    <path d="M11.9401 2.40767L11.9401 21.5942" stroke="#085CAF" stroke-width="3" stroke-linecap="round" stroke-linejoin="round"></path>
                                                                                </svg>
                                                                            </button>
                                                                        </div>
                                                                        <div class="Header__bottom--mSn+X">
                                                                            <div>
                                                                                <button class="Header__title--W0rcU">
                                                                                    <span class="Header__url--+cB+Z Header__linked--TcvJ0">Create the sales order page</span>
                                                                                </button>
                                                                                <div class="Header__wrapper--XNMcL"></div>
                                                                            </div>
                                                                        </div>
                                                                        <div class="Expander__wrapper--GK6+l">
                                                                            <div class="Expander__hide--Q-ULJ">
                                                                                <div class="Expander__separator--dU1cP"></div>
                                                                                <div>
                                                                                    <div>
                                                                                        <ul class="ConditionalContent__tabsList--gdp6i">
                                                                                            <li class="Tab__tab--Yfom7 Tab__active--Hasi3">
                                                                                                <button class="Tab__button--++n+9" title="Open Basic steps">Basic steps</button>
                                                                                            </li>
                                                                                            <li class="Tab__tab--Yfom7">
                                                                                                <button class="Tab__button--++n+9" title="Open Import Project">Import Project</button>
                                                                                            </li>
                                                                                        </ul>
                                                                                        <div class="tutorialBody">
                                                                                            <p>By default your new application contains a page with title and text fields. In this step, you will focus on turning this page into your app, including how to build a UI and stylize the UI elements.</p>
                                                                                            <blockquote>
                                                                                                <p>Note that there are 2 tabs for this step. </p>
                                                                                                <ul>
                                                                                                    <li>
                                                                                                        <p>
                                                                                                            You can do the first tab, <strong>Basic steps</strong>
                                                                                                            , which we recommend and which will teach you about UI components, stylizing them, and organizing them on the page.
                                                                                                        </p>
                                                                                                    </li>
                                                                                                    <li>
                                                                                                        <p>
                                                                                                            You can instead do the second tab, <strong>Import Project</strong>
                                                                                                            , which will bypass the nitty gritty of adding and stylizing components, and instead teach you how to import an SAP Build Apps project into an existing project. This way is much faster.
                                                                                                        </p>
                                                                                                    </li>
                                                                                                </ul>
                                                                                            </blockquote>
                                                                                            <div class="conditionalStep" data-system-type="Basic steps"></div>
                                                                                            <div class="conditionalStep" data-system-type="Import Project"></div>
                                                                                        </div>
                                                                                        <div class="SubmitButton__root--QWQTU">
                                                                                            <span>
                                                                                                <a href="/bin/fiji/es/login.sapdxdevs.html" title="Log in">Log in</a>
                                                                                                to complete tutorial
                                                                                            </span>
                                                                                            <button disabled="" class="SubmitButton__button--I7eWM SubmitButton__disabled--V-NkW">Done</button>
                                                                                        </div>
                                                                                    </div>
                                                                                </div>
                                                                            </div>
                                                                        </div>
                                                                    </div>
                                                                </li>
                                                                <li id="cd08140d-144e-4695-bae0-4cfd84f1aa7e" class="Accordion__item--DNzPY">
                                                                    <div class="Expander__expander--4DOyC">
                                                                        <div class="Top__top--kjtjD">
                                                                            <div class="Top__type--CI8yu">
                                                                                <span class="Status__status--ucVFH Top__chained--TywwF">
                                                                                    <svg width="20" height="20" viewBox="0 0 20 20" fill="none" xmlns="http://www.w3.org/2000/svg">
                                                                                        <circle cx="10" cy="10" r="9.5" fill="#EAEBEE" stroke="#B1B1B1"></circle>
                                                                                    </svg>
                                                                                </span>
                                                                                <span class="Top__title--BIOWY">Step 3</span>
                                                                            </div>
                                                                            <button class="ExpanderButton__expanderButton--2JY9n" title="Collapse content" aria-label="Toggle accordion">
                                                                                <svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                                                                                    <path fill-rule="evenodd" clip-rule="evenodd" d="M2.40474 12.0001H21.4744H2.40474Z" fill="#003283"></path>
                                                                                    <path d="M2.40474 12.0001H21.4744" stroke="#085CAF" stroke-width="3" stroke-linecap="round" stroke-linejoin="round"></path>
                                                                                    <path fill-rule="evenodd" clip-rule="evenodd" d="M11.9401 2.40767L11.9401 21.5942L11.9401 2.40767Z" fill="#003283"></path>
                                                                                    <path d="M11.9401 2.40767L11.9401 21.5942" stroke="#085CAF" stroke-width="3" stroke-linecap="round" stroke-linejoin="round"></path>
                                                                                </svg>
                                                                            </button>
                                                                        </div>
                                                                        <div class="Header__bottom--mSn+X">
                                                                            <div>
                                                                                <button class="Header__title--W0rcU">
                                                                                    <span class="Header__url--+cB+Z Header__linked--TcvJ0">Enable SAP BTP authentication</span>
                                                                                </button>
                                                                                <div class="Header__wrapper--XNMcL"></div>
                                                                            </div>
                                                                        </div>
                                                                        <div class="Expander__wrapper--GK6+l">
                                                                            <div class="Expander__hide--Q-ULJ">
                                                                                <div class="Expander__separator--dU1cP"></div>
                                                                                <div>
                                                                                    <div>
                                                                                        <div class="tutorialBody">
                                                                                            <p>You need to enable SAP BTP authentication since you want to use SAP BTP destinations.</p>
                                                                                            <ol>
                                                                                                <li>
                                                                                                    <p>
                                                                                                        Go to the <strong>Auth</strong>
                                                                                                        tab.
                                                                                                    </p>
                                                                                                </li>
                                                                                                <li>
                                                                                                    <p>
                                                                                                        Click <strong>Enable Authentication</strong>
                                                                                                        .
                                                                                                    </p>
                                                                                                    <div class="img-zoom img-zoom__hidden">
                                                                                                        <div class="enlarge-icon">
                                                                                                            <svg width="40px" height="40px" viewBox="0 0 40 40" version="1.1" xmlns="http://www.w3.org/2000/svg">
                                                                                                                <g id="Atoms/Icons/Enlarge" stroke="none" stroke-width="1" fill="none" fill-rule="evenodd">
                                                                                                                    <rect id="Rectangle" fill="#E9E9E9" opacity="0.8" x="0" y="0" width="40" height="40" rx="4"></rect>
                                                                                                                    <g id="enlarge-icon" transform="translate(8.000000, 8.000000)" fill="#000000" fill-rule="nonzero">
                                                                                                                        <polygon id="Path" points="24 0 14.25 0 18 3.75 13.5 8.25 15.75 10.5 20.25 6 24 9.75"></polygon>
                                                                                                                        <polygon id="Path" points="24 24 24 14.25 20.25 18 15.75 13.5 13.5 15.75 18 20.25 14.25 24"></polygon>
                                                                                                                        <polygon id="Path" points="0 24 9.75 24 6 20.25 10.5 15.75 8.25 13.5 3.75 18 0 14.25"></polygon>
                                                                                                                        <polygon id="Path" points="0 0 0 9.75 3.75 6 8.25 10.5 10.5 8.25 6 3.75 9.75 0"></polygon>
                                                                                                                    </g>
                                                                                                                </g>
                                                                                                            </svg>
                                                                                                        </div>
                                                                                                        <img src="/tutorials/build-apps-workflow-trigger/_jcr_content.github-proxy.1678009502.file/auth.png" alt="Auth"/>
                                                                                                    </div>
                                                                                                </li>
                                                                                                <li>
                                                                                                    <p>
                                                                                                        Select <strong>SAP BTP Authentication</strong>
                                                                                                        .
                                                                                                    </p>
                                                                                                    <p>
                                                                                                        On the confirmation popup, click <strong>OK</strong>
                                                                                                        .
                                                                                                    </p>
                                                                                                </li>
                                                                                            </ol>
                                                                                        </div>
                                                                                        <div class="SubmitButton__root--QWQTU">
                                                                                            <span>
                                                                                                <a href="/bin/fiji/es/login.sapdxdevs.html" title="Log in">Log in</a>
                                                                                                to complete tutorial
                                                                                            </span>
                                                                                            <button disabled="" class="SubmitButton__button--I7eWM SubmitButton__disabled--V-NkW">Done</button>
                                                                                        </div>
                                                                                    </div>
                                                                                </div>
                                                                            </div>
                                                                        </div>
                                                                    </div>
                                                                </li>
                                                                <li id="78aa568e-8deb-4bf0-9d16-b71146094511" class="Accordion__item--DNzPY">
                                                                    <div class="Expander__expander--4DOyC">
                                                                        <div class="Top__top--kjtjD">
                                                                            <div class="Top__type--CI8yu">
                                                                                <span class="Status__status--ucVFH Top__chained--TywwF">
                                                                                    <svg width="20" height="20" viewBox="0 0 20 20" fill="none" xmlns="http://www.w3.org/2000/svg">
                                                                                        <circle cx="10" cy="10" r="9.5" fill="#EAEBEE" stroke="#B1B1B1"></circle>
                                                                                    </svg>
                                                                                </span>
                                                                                <span class="Top__title--BIOWY">Step 4</span>
                                                                            </div>
                                                                            <button class="ExpanderButton__expanderButton--2JY9n" title="Collapse content" aria-label="Toggle accordion">
                                                                                <svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                                                                                    <path fill-rule="evenodd" clip-rule="evenodd" d="M2.40474 12.0001H21.4744H2.40474Z" fill="#003283"></path>
                                                                                    <path d="M2.40474 12.0001H21.4744" stroke="#085CAF" stroke-width="3" stroke-linecap="round" stroke-linejoin="round"></path>
                                                                                    <path fill-rule="evenodd" clip-rule="evenodd" d="M11.9401 2.40767L11.9401 21.5942L11.9401 2.40767Z" fill="#003283"></path>
                                                                                    <path d="M11.9401 2.40767L11.9401 21.5942" stroke="#085CAF" stroke-width="3" stroke-linecap="round" stroke-linejoin="round"></path>
                                                                                </svg>
                                                                            </button>
                                                                        </div>
                                                                        <div class="Header__bottom--mSn+X">
                                                                            <div>
                                                                                <button class="Header__title--W0rcU">
                                                                                    <span class="Header__url--+cB+Z Header__linked--TcvJ0">Create data resource to SAP Build Process Automation</span>
                                                                                </button>
                                                                                <div class="Header__wrapper--XNMcL"></div>
                                                                            </div>
                                                                        </div>
                                                                        <div class="Expander__wrapper--GK6+l">
                                                                            <div class="Expander__hide--Q-ULJ">
                                                                                <div class="Expander__separator--dU1cP"></div>
                                                                                <div>
                                                                                    <div>
                                                                                        <div class="tutorialBody">
                                                                                            <p>As part of setting up SAP Build Process Automation, you created a destination so you can make calls to the SAP Build Process Automation APIs, including the one that lets you trigger a workflow.</p>
                                                                                            <p>Now you will set up the connection from your app to SAP Build Process Automation on your tenant, using that destination.</p>
                                                                                            <ol>
                                                                                                <li>
                                                                                                    <p>
                                                                                                        Open the <strong>Data</strong>
                                                                                                        tab, at the top of the page.
                                                                                                    </p>
                                                                                                </li>
                                                                                                <li>
                                                                                                    <p>
                                                                                                        Scroll down, and click <strong>Create Data Entity &gt;SAP BTP Destination REST API Integration</strong>
                                                                                                        .
                                                                                                    </p>
                                                                                                    <div class="img-zoom img-zoom__hidden">
                                                                                                        <div class="enlarge-icon">
                                                                                                            <svg width="40px" height="40px" viewBox="0 0 40 40" version="1.1" xmlns="http://www.w3.org/2000/svg">
                                                                                                                <g id="Atoms/Icons/Enlarge" stroke="none" stroke-width="1" fill="none" fill-rule="evenodd">
                                                                                                                    <rect id="Rectangle" fill="#E9E9E9" opacity="0.8" x="0" y="0" width="40" height="40" rx="4"></rect>
                                                                                                                    <g id="enlarge-icon" transform="translate(8.000000, 8.000000)" fill="#000000" fill-rule="nonzero">
                                                                                                                        <polygon id="Path" points="24 0 14.25 0 18 3.75 13.5 8.25 15.75 10.5 20.25 6 24 9.75"></polygon>
                                                                                                                        <polygon id="Path" points="24 24 24 14.25 20.25 18 15.75 13.5 13.5 15.75 18 20.25 14.25 24"></polygon>
                                                                                                                        <polygon id="Path" points="0 24 9.75 24 6 20.25 10.5 15.75 8.25 13.5 3.75 18 0 14.25"></polygon>
                                                                                                                        <polygon id="Path" points="0 0 0 9.75 3.75 6 8.25 10.5 10.5 8.25 6 3.75 9.75 0"></polygon>
                                                                                                                    </g>
                                                                                                                </g>
                                                                                                            </svg>
                                                                                                        </div>
                                                                                                        <img src="/tutorials/build-apps-workflow-trigger/_jcr_content.github-proxy.1678009502.file/data-resource-new.png" alt="New data resource"/>
                                                                                                    </div>
                                                                                                    <p>
                                                                                                        The configuration screen appears, starting with the <strong>Base</strong>
                                                                                                        panel.
                                                                                                    </p>
                                                                                                </li>
                                                                                                <li>
                                                                                                    <p>
                                                                                                        On the <strong>Base</strong>
                                                                                                        panel, enter the following:
                                                                                                    </p>
                                                                                                    <table>
                                                                                                        <thead>
                                                                                                            <tr>
                                                                                                                <th>Field </th>
                                                                                                                <th>Value </th>
                                                                                                            </tr>
                                                                                                        </thead>
                                                                                                        <tbody>
                                                                                                            <tr>
                                                                                                                <td>Data resource name </td>
                                                                                                                <td>
                                                                                                                    <code>Trigger Workflow</code>
                                                                                                                </td>
                                                                                                            </tr>
                                                                                                            <tr>
                                                                                                                <td>BTP destination name </td>
                                                                                                                <td>
                                                                                                                    <code>sap-process-destination</code>
                                                                                                                    (or the destination you created, if you created your own) 
                                                                                                                </td>
                                                                                                            </tr>
                                                                                                        </tbody>
                                                                                                    </table>
                                                                                                    <div class="img-zoom img-zoom__hidden">
                                                                                                        <div class="enlarge-icon">
                                                                                                            <svg width="40px" height="40px" viewBox="0 0 40 40" version="1.1" xmlns="http://www.w3.org/2000/svg">
                                                                                                                <g id="Atoms/Icons/Enlarge" stroke="none" stroke-width="1" fill="none" fill-rule="evenodd">
                                                                                                                    <rect id="Rectangle" fill="#E9E9E9" opacity="0.8" x="0" y="0" width="40" height="40" rx="4"></rect>
                                                                                                                    <g id="enlarge-icon" transform="translate(8.000000, 8.000000)" fill="#000000" fill-rule="nonzero">
                                                                                                                        <polygon id="Path" points="24 0 14.25 0 18 3.75 13.5 8.25 15.75 10.5 20.25 6 24 9.75"></polygon>
                                                                                                                        <polygon id="Path" points="24 24 24 14.25 20.25 18 15.75 13.5 13.5 15.75 18 20.25 14.25 24"></polygon>
                                                                                                                        <polygon id="Path" points="0 24 9.75 24 6 20.25 10.5 15.75 8.25 13.5 3.75 18 0 14.25"></polygon>
                                                                                                                        <polygon id="Path" points="0 0 0 9.75 3.75 6 8.25 10.5 10.5 8.25 6 3.75 9.75 0"></polygon>
                                                                                                                    </g>
                                                                                                                </g>
                                                                                                            </svg>
                                                                                                        </div>
                                                                                                        <img src="/tutorials/build-apps-workflow-trigger/_jcr_content.github-proxy.1678009502.file/data-resource-base.png" alt="Base"/>
                                                                                                    </div>
                                                                                                    <p>
                                                                                                        Under <strong>Resource schema</strong>
                                                                                                        , click <strong>Add New</strong>
                                                                                                        and add a field of type 
                                                                                                        <strong>
                                                                                                            <em>Object</em>
                                                                                                        </strong>
                                                                                                        and with the name <code>salesorderdetails</code>
                                                                                                        .
                                                                                                    </p>
                                                                                                    <p>Click on the new field, and add the following sub-fields to the object:</p>
                                                                                                    <div class="img-zoom img-zoom__hidden">
                                                                                                        <div class="enlarge-icon">
                                                                                                            <svg width="40px" height="40px" viewBox="0 0 40 40" version="1.1" xmlns="http://www.w3.org/2000/svg">
                                                                                                                <g id="Atoms/Icons/Enlarge" stroke="none" stroke-width="1" fill="none" fill-rule="evenodd">
                                                                                                                    <rect id="Rectangle" fill="#E9E9E9" opacity="0.8" x="0" y="0" width="40" height="40" rx="4"></rect>
                                                                                                                    <g id="enlarge-icon" transform="translate(8.000000, 8.000000)" fill="#000000" fill-rule="nonzero">
                                                                                                                        <polygon id="Path" points="24 0 14.25 0 18 3.75 13.5 8.25 15.75 10.5 20.25 6 24 9.75"></polygon>
                                                                                                                        <polygon id="Path" points="24 24 24 14.25 20.25 18 15.75 13.5 13.5 15.75 18 20.25 14.25 24"></polygon>
                                                                                                                        <polygon id="Path" points="0 24 9.75 24 6 20.25 10.5 15.75 8.25 13.5 3.75 18 0 14.25"></polygon>
                                                                                                                        <polygon id="Path" points="0 0 0 9.75 3.75 6 8.25 10.5 10.5 8.25 6 3.75 9.75 0"></polygon>
                                                                                                                    </g>
                                                                                                                </g>
                                                                                                            </svg>
                                                                                                        </div>
                                                                                                        <img src="/tutorials/build-apps-workflow-trigger/_jcr_content.github-proxy.1678009502.file/data-resource-base2.png" alt="Base parameters"/>
                                                                                                    </div>
                                                                                                    <blockquote>
                                                                                                        <p>
                                                                                                            <strong>IMPORTANT:</strong>
                                                                                                            Click on the <strong>Add New</strong>
                                                                                                            button <strong>BELOW</strong>
                                                                                                            the <code>salesorderdetails</code>
                                                                                                            field.
                                                                                                        </p>
                                                                                                    </blockquote>
                                                                                                    <table>
                                                                                                        <thead>
                                                                                                            <tr>
                                                                                                                <th>Field Name </th>
                                                                                                                <th>Type </th>
                                                                                                            </tr>
                                                                                                        </thead>
                                                                                                        <tbody>
                                                                                                            <tr>
                                                                                                                <td>
                                                                                                                    <strong>
                                                                                                                        <code>ShipToParty</code>
                                                                                                                    </strong>
                                                                                                                </td>
                                                                                                                <td>
                                                                                                                    <strong>
                                                                                                                        <em>Text</em>
                                                                                                                    </strong>
                                                                                                                </td>
                                                                                                            </tr>
                                                                                                            <tr>
                                                                                                                <td>
                                                                                                                    <strong>
                                                                                                                        <code>Material</code>
                                                                                                                    </strong>
                                                                                                                </td>
                                                                                                                <td>
                                                                                                                    <strong>
                                                                                                                        <em>Text</em>
                                                                                                                    </strong>
                                                                                                                </td>
                                                                                                            </tr>
                                                                                                            <tr>
                                                                                                                <td>
                                                                                                                    <strong>
                                                                                                                        <code>OrderAmount</code>
                                                                                                                    </strong>
                                                                                                                </td>
                                                                                                                <td>
                                                                                                                    <strong>
                                                                                                                        <em>Number</em>
                                                                                                                    </strong>
                                                                                                                </td>
                                                                                                            </tr>
                                                                                                            <tr>
                                                                                                                <td>
                                                                                                                    <strong>
                                                                                                                        <code>ExpectedDeliveryDate</code>
                                                                                                                    </strong>
                                                                                                                </td>
                                                                                                                <td>
                                                                                                                    <strong>
                                                                                                                        <em>Text</em>
                                                                                                                    </strong>
                                                                                                                </td>
                                                                                                            </tr>
                                                                                                            <tr>
                                                                                                                <td>
                                                                                                                    <strong>
                                                                                                                        <code>Division</code>
                                                                                                                    </strong>
                                                                                                                </td>
                                                                                                                <td>
                                                                                                                    <strong>
                                                                                                                        <em>Text</em>
                                                                                                                    </strong>
                                                                                                                </td>
                                                                                                            </tr>
                                                                                                            <tr>
                                                                                                                <td>
                                                                                                                    <strong>
                                                                                                                        <code>SalesOrderType</code>
                                                                                                                    </strong>
                                                                                                                </td>
                                                                                                                <td>
                                                                                                                    <strong>
                                                                                                                        <em>Text</em>
                                                                                                                    </strong>
                                                                                                                </td>
                                                                                                            </tr>
                                                                                                            <tr>
                                                                                                                <td>
                                                                                                                    <strong>
                                                                                                                        <code>ShippingCountry</code>
                                                                                                                    </strong>
                                                                                                                </td>
                                                                                                                <td>
                                                                                                                    <strong>
                                                                                                                        <em>Text</em>
                                                                                                                    </strong>
                                                                                                                </td>
                                                                                                            </tr>
                                                                                                            <tr>
                                                                                                                <td>
                                                                                                                    <strong>
                                                                                                                        <code>SalesOrganisation</code>
                                                                                                                    </strong>
                                                                                                                </td>
                                                                                                                <td>
                                                                                                                    <strong>
                                                                                                                        <em>Text</em>
                                                                                                                    </strong>
                                                                                                                </td>
                                                                                                            </tr>
                                                                                                            <tr>
                                                                                                                <td>
                                                                                                                    <strong>
                                                                                                                        <code>DistributionChannel</code>
                                                                                                                    </strong>
                                                                                                                </td>
                                                                                                                <td>
                                                                                                                    <strong>
                                                                                                                        <em>Text</em>
                                                                                                                    </strong>
                                                                                                                </td>
                                                                                                            </tr>
                                                                                                        </tbody>
                                                                                                    </table>
                                                                                                </li>
                                                                                                <li>
                                                                                                    <p>
                                                                                                        Click the <strong>create</strong>
                                                                                                        panel.
                                                                                                    </p>
                                                                                                    <p>Then enable the create action with the toggle button.</p>
                                                                                                    <div class="img-zoom img-zoom__hidden">
                                                                                                        <div class="enlarge-icon">
                                                                                                            <svg width="40px" height="40px" viewBox="0 0 40 40" version="1.1" xmlns="http://www.w3.org/2000/svg">
                                                                                                                <g id="Atoms/Icons/Enlarge" stroke="none" stroke-width="1" fill="none" fill-rule="evenodd">
                                                                                                                    <rect id="Rectangle" fill="#E9E9E9" opacity="0.8" x="0" y="0" width="40" height="40" rx="4"></rect>
                                                                                                                    <g id="enlarge-icon" transform="translate(8.000000, 8.000000)" fill="#000000" fill-rule="nonzero">
                                                                                                                        <polygon id="Path" points="24 0 14.25 0 18 3.75 13.5 8.25 15.75 10.5 20.25 6 24 9.75"></polygon>
                                                                                                                        <polygon id="Path" points="24 24 24 14.25 20.25 18 15.75 13.5 13.5 15.75 18 20.25 14.25 24"></polygon>
                                                                                                                        <polygon id="Path" points="0 24 9.75 24 6 20.25 10.5 15.75 8.25 13.5 3.75 18 0 14.25"></polygon>
                                                                                                                        <polygon id="Path" points="0 0 0 9.75 3.75 6 8.25 10.5 10.5 8.25 6 3.75 9.75 0"></polygon>
                                                                                                                    </g>
                                                                                                                </g>
                                                                                                            </svg>
                                                                                                        </div>
                                                                                                        <img src="/tutorials/build-apps-workflow-trigger/_jcr_content.github-proxy.1678009502.file/create.png" alt="Create enable"/>
                                                                                                    </div>
                                                                                                    <br/>
                                                                                                    <div class="img-zoom img-zoom__hidden">
                                                                                                        <div class="enlarge-icon">
                                                                                                            <svg width="40px" height="40px" viewBox="0 0 40 40" version="1.1" xmlns="http://www.w3.org/2000/svg">
                                                                                                                <g id="Atoms/Icons/Enlarge" stroke="none" stroke-width="1" fill="none" fill-rule="evenodd">
                                                                                                                    <rect id="Rectangle" fill="#E9E9E9" opacity="0.8" x="0" y="0" width="40" height="40" rx="4"></rect>
                                                                                                                    <g id="enlarge-icon" transform="translate(8.000000, 8.000000)" fill="#000000" fill-rule="nonzero">
                                                                                                                        <polygon id="Path" points="24 0 14.25 0 18 3.75 13.5 8.25 15.75 10.5 20.25 6 24 9.75"></polygon>
                                                                                                                        <polygon id="Path" points="24 24 24 14.25 20.25 18 15.75 13.5 13.5 15.75 18 20.25 14.25 24"></polygon>
                                                                                                                        <polygon id="Path" points="0 24 9.75 24 6 20.25 10.5 15.75 8.25 13.5 3.75 18 0 14.25"></polygon>
                                                                                                                        <polygon id="Path" points="0 0 0 9.75 3.75 6 8.25 10.5 10.5 8.25 6 3.75 9.75 0"></polygon>
                                                                                                                    </g>
                                                                                                                </g>
                                                                                                            </svg>
                                                                                                        </div>
                                                                                                        <img src="/tutorials/build-apps-workflow-trigger/_jcr_content.github-proxy.1678009502.file/data-resource-create.png" alt="Create enable"/>
                                                                                                    </div>
                                                                                                </li>
                                                                                                <li>
                                                                                                    <p>
                                                                                                        For <strong>Request headers</strong>
                                                                                                        , click the binding <strong>X</strong>
                                                                                                        , then <strong>List of values</strong>
                                                                                                        .
                                                                                                    </p>
                                                                                                    <p>
                                                                                                        Click <strong>Add a value</strong>
                                                                                                        , and add the following key-value pair:
                                                                                                    </p>
                                                                                                    <table>
                                                                                                        <thead>
                                                                                                            <tr>
                                                                                                                <th>Field </th>
                                                                                                                <th>Value </th>
                                                                                                            </tr>
                                                                                                        </thead>
                                                                                                        <tbody>
                                                                                                            <tr>
                                                                                                                <td>
                                                                                                                    <strong>Header name</strong>
                                                                                                                </td>
                                                                                                                <td>
                                                                                                                    <code>Content-Type</code>
                                                                                                                </td>
                                                                                                            </tr>
                                                                                                            <tr>
                                                                                                                <td>
                                                                                                                    <strong>Header value</strong>
                                                                                                                </td>
                                                                                                                <td>
                                                                                                                    <code>application/json</code>
                                                                                                                </td>
                                                                                                            </tr>
                                                                                                        </tbody>
                                                                                                    </table>
                                                                                                    <p>
                                                                                                        Click <strong>Save</strong>
                                                                                                        .
                                                                                                    </p>
                                                                                                </li>
                                                                                                <li>
                                                                                                    <p>
                                                                                                        For <strong>Request body mapper</strong>
                                                                                                        , click the binding <strong>X</strong>
                                                                                                        , then <strong>Formula &gt;Create formula</strong>
                                                                                                        .
                                                                                                    </p>
                                                                                                    <p>
                                                                                                        Enter the following for the formula – replace <code>&lt;your definition ID &gt;</code>
                                                                                                        with the ID for your process:
                                                                                                    </p>
                                                                                                    <div class="code-header">
                                                                                                        <div class="language">JavaScript</div>
                                                                                                        <div class="copy">Copy</div>
                                                                                                    </div>
                                                                                                    <pre data-line="">
                                                                                                        <code class="line-numbers language-javascript">ENCODE_JSON({  &quot;definitionId &quot;: &quot;&lt;your definition ID &gt;&quot;,  &quot;context &quot;:  query.record })
</code>
                                                                                                    </pre>
                                                                                                    <p>
                                                                                                        Click <strong>Save</strong>
                                                                                                        twice.
                                                                                                    </p>
                                                                                                </li>
                                                                                                <li>
                                                                                                    <p>
                                                                                                        Click <strong>Save Data Resource</strong>
                                                                                                        (bottom right).
                                                                                                    </p>
                                                                                                    <p>
                                                                                                        Click <strong>Save</strong>
                                                                                                        (in the upper right to save all your changes to the project).
                                                                                                    </p>
                                                                                                </li>
                                                                                            </ol>
                                                                                        </div>
                                                                                        <div class="SubmitButton__root--QWQTU">
                                                                                            <span>
                                                                                                <a href="/bin/fiji/es/login.sapdxdevs.html" title="Log in">Log in</a>
                                                                                                to complete tutorial
                                                                                            </span>
                                                                                            <button disabled="" class="SubmitButton__button--I7eWM SubmitButton__disabled--V-NkW">Done</button>
                                                                                        </div>
                                                                                    </div>
                                                                                </div>
                                                                            </div>
                                                                        </div>
                                                                    </div>
                                                                </li>
                                                                <li id="4be04d79-e6a0-43a1-874f-fdeb81f7cc61" class="Accordion__item--DNzPY">
                                                                    <div class="Expander__expander--4DOyC">
                                                                        <div class="Top__top--kjtjD">
                                                                            <div class="Top__type--CI8yu">
                                                                                <span class="Status__status--ucVFH Top__chained--TywwF">
                                                                                    <svg width="20" height="20" viewBox="0 0 20 20" fill="none" xmlns="http://www.w3.org/2000/svg">
                                                                                        <circle cx="10" cy="10" r="9.5" fill="#EAEBEE" stroke="#B1B1B1"></circle>
                                                                                    </svg>
                                                                                </span>
                                                                                <span class="Top__title--BIOWY">Step 5</span>
                                                                            </div>
                                                                            <button class="ExpanderButton__expanderButton--2JY9n" title="Collapse content" aria-label="Toggle accordion">
                                                                                <svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                                                                                    <path fill-rule="evenodd" clip-rule="evenodd" d="M2.40474 12.0001H21.4744H2.40474Z" fill="#003283"></path>
                                                                                    <path d="M2.40474 12.0001H21.4744" stroke="#085CAF" stroke-width="3" stroke-linecap="round" stroke-linejoin="round"></path>
                                                                                    <path fill-rule="evenodd" clip-rule="evenodd" d="M11.9401 2.40767L11.9401 21.5942L11.9401 2.40767Z" fill="#003283"></path>
                                                                                    <path d="M11.9401 2.40767L11.9401 21.5942" stroke="#085CAF" stroke-width="3" stroke-linecap="round" stroke-linejoin="round"></path>
                                                                                </svg>
                                                                            </button>
                                                                        </div>
                                                                        <div class="Header__bottom--mSn+X">
                                                                            <div>
                                                                                <button class="Header__title--W0rcU">
                                                                                    <span class="Header__url--+cB+Z Header__linked--TcvJ0">Test the trigger</span>
                                                                                </button>
                                                                                <div class="Header__wrapper--XNMcL"></div>
                                                                            </div>
                                                                        </div>
                                                                        <div class="Expander__wrapper--GK6+l">
                                                                            <div class="Expander__hide--Q-ULJ">
                                                                                <div class="Expander__separator--dU1cP"></div>
                                                                                <div>
                                                                                    <div>
                                                                                        <div class="tutorialBody">
                                                                                            <ol>
                                                                                                <li>
                                                                                                    <p>Open the data resource again by clicking it.</p>
                                                                                                    <div class="img-zoom img-zoom__hidden">
                                                                                                        <div class="enlarge-icon">
                                                                                                            <svg width="40px" height="40px" viewBox="0 0 40 40" version="1.1" xmlns="http://www.w3.org/2000/svg">
                                                                                                                <g id="Atoms/Icons/Enlarge" stroke="none" stroke-width="1" fill="none" fill-rule="evenodd">
                                                                                                                    <rect id="Rectangle" fill="#E9E9E9" opacity="0.8" x="0" y="0" width="40" height="40" rx="4"></rect>
                                                                                                                    <g id="enlarge-icon" transform="translate(8.000000, 8.000000)" fill="#000000" fill-rule="nonzero">
                                                                                                                        <polygon id="Path" points="24 0 14.25 0 18 3.75 13.5 8.25 15.75 10.5 20.25 6 24 9.75"></polygon>
                                                                                                                        <polygon id="Path" points="24 24 24 14.25 20.25 18 15.75 13.5 13.5 15.75 18 20.25 14.25 24"></polygon>
                                                                                                                        <polygon id="Path" points="0 24 9.75 24 6 20.25 10.5 15.75 8.25 13.5 3.75 18 0 14.25"></polygon>
                                                                                                                        <polygon id="Path" points="0 0 0 9.75 3.75 6 8.25 10.5 10.5 8.25 6 3.75 9.75 0"></polygon>
                                                                                                                    </g>
                                                                                                                </g>
                                                                                                            </svg>
                                                                                                        </div>
                                                                                                        <img src="/tutorials/build-apps-workflow-trigger/_jcr_content.github-proxy.1678009502.file/test-open.png" alt="Test open"/>
                                                                                                    </div>
                                                                                                </li>
                                                                                                <li>
                                                                                                    <p>
                                                                                                        Click <strong>create</strong>
                                                                                                        on the left, and then the <strong>Test</strong>
                                                                                                        tab.
                                                                                                    </p>
                                                                                                </li>
                                                                                                <li>
                                                                                                    <p>
                                                                                                        Enter values for the fields (really, you only need to enter an order amount), and then scroll down and click <strong>Run Test</strong>
                                                                                                        .
                                                                                                    </p>
                                                                                                    <blockquote>
                                                                                                        <p>
                                                                                                            <strong>IMPORTANT:</strong>
                                                                                                            Date fields must be in the format of <code>2022-12-25</code>
                                                                                                            and the order amount must be a number.
                                                                                                        </p>
                                                                                                    </blockquote>
                                                                                                    <div class="img-zoom img-zoom__hidden">
                                                                                                        <div class="enlarge-icon">
                                                                                                            <svg width="40px" height="40px" viewBox="0 0 40 40" version="1.1" xmlns="http://www.w3.org/2000/svg">
                                                                                                                <g id="Atoms/Icons/Enlarge" stroke="none" stroke-width="1" fill="none" fill-rule="evenodd">
                                                                                                                    <rect id="Rectangle" fill="#E9E9E9" opacity="0.8" x="0" y="0" width="40" height="40" rx="4"></rect>
                                                                                                                    <g id="enlarge-icon" transform="translate(8.000000, 8.000000)" fill="#000000" fill-rule="nonzero">
                                                                                                                        <polygon id="Path" points="24 0 14.25 0 18 3.75 13.5 8.25 15.75 10.5 20.25 6 24 9.75"></polygon>
                                                                                                                        <polygon id="Path" points="24 24 24 14.25 20.25 18 15.75 13.5 13.5 15.75 18 20.25 14.25 24"></polygon>
                                                                                                                        <polygon id="Path" points="0 24 9.75 24 6 20.25 10.5 15.75 8.25 13.5 3.75 18 0 14.25"></polygon>
                                                                                                                        <polygon id="Path" points="0 0 0 9.75 3.75 6 8.25 10.5 10.5 8.25 6 3.75 9.75 0"></polygon>
                                                                                                                    </g>
                                                                                                                </g>
                                                                                                            </svg>
                                                                                                        </div>
                                                                                                        <img src="/tutorials/build-apps-workflow-trigger/_jcr_content.github-proxy.1678009502.file/test-parameters.png" alt="Test parameters"/>
                                                                                                    </div>
                                                                                                </li>
                                                                                            </ol>
                                                                                            <p>
                                                                                                If all works OK, you will get a <strong>201</strong>
                                                                                                status code and a response with information about the process instance you just triggered, something like this:
                                                                                            </p>
                                                                                            <div class="code-header">
                                                                                                <div class="language">JavaScript</div>
                                                                                                <div class="copy">Copy</div>
                                                                                            </div>
                                                                                            <pre data-line="">
                                                                                                <code class="line-numbers language-javascript">{
  &quot;id &quot;: &quot;54988e48-8056-11ed-9a13-eeee0a99244a &quot;,
  &quot;definitionId &quot;: &quot;us10.my-account.salesorderapprovals.orderProcessing &quot;,
  &quot;definitionVersion &quot;: &quot;6 &quot;,
  &quot;subject &quot;: &quot;Order Processing &quot;,
  &quot;status &quot;: &quot;RUNNING &quot;,
  &quot;businessKey &quot;: &quot;54988e48-8056-11ed-9a13-eeee0a99244a &quot;,
  &quot;parentInstanceId &quot;: null,
  &quot;rootInstanceId &quot;: &quot;11118e48-8056-11ed-9a13-eeee0a99244a &quot;,
  &quot;applicationScope &quot;: &quot;own &quot;,
  &quot;projectId &quot;: &quot;us10.my-account.salesorderapprovals &quot;,
  &quot;projectVersion &quot;: &quot;1.0.5 &quot;,
  &quot;startedAt &quot;: &quot;2022-12-20T11:06:19.318Z &quot;,
  &quot;startedBy &quot;: &quot;sb-clone-41c25609-33a1-9999-97d8-34fcd2316008!b3591|workflow!b116 &quot;,
  &quot;completedAt &quot;: null
}
</code>
                                                                                            </pre>
                                                                                            <div class="img-zoom img-zoom__hidden">
                                                                                                <div class="enlarge-icon">
                                                                                                    <svg width="40px" height="40px" viewBox="0 0 40 40" version="1.1" xmlns="http://www.w3.org/2000/svg">
                                                                                                        <g id="Atoms/Icons/Enlarge" stroke="none" stroke-width="1" fill="none" fill-rule="evenodd">
                                                                                                            <rect id="Rectangle" fill="#E9E9E9" opacity="0.8" x="0" y="0" width="40" height="40" rx="4"></rect>
                                                                                                            <g id="enlarge-icon" transform="translate(8.000000, 8.000000)" fill="#000000" fill-rule="nonzero">
                                                                                                                <polygon id="Path" points="24 0 14.25 0 18 3.75 13.5 8.25 15.75 10.5 20.25 6 24 9.75"></polygon>
                                                                                                                <polygon id="Path" points="24 24 24 14.25 20.25 18 15.75 13.5 13.5 15.75 18 20.25 14.25 24"></polygon>
                                                                                                                <polygon id="Path" points="0 24 9.75 24 6 20.25 10.5 15.75 8.25 13.5 3.75 18 0 14.25"></polygon>
                                                                                                                <polygon id="Path" points="0 0 0 9.75 3.75 6 8.25 10.5 10.5 8.25 6 3.75 9.75 0"></polygon>
                                                                                                            </g>
                                                                                                        </g>
                                                                                                    </svg>
                                                                                                </div>
                                                                                                <img src="/tutorials/build-apps-workflow-trigger/_jcr_content.github-proxy.1678009502.file/test-response.png" alt="Test response"/>
                                                                                            </div>
                                                                                            <blockquote>
                                                                                                <p>
                                                                                                    <strong>COMMON ISSUES</strong>
                                                                                                </p>
                                                                                                <p>
                                                                                                    <strong>404:</strong>
                                                                                                    The API did not recognize the name of your process (i.e., <code>definitionId</code>
                                                                                                    in the request body mapper) or the path to the service is wrong – both in the <strong>create</strong>
                                                                                                    tab.
                                                                                                </p>
                                                                                                <p>
                                                                                                    <strong>415:</strong>
                                                                                                    You did not send the <code>Content-Type</code>
                                                                                                    request header.
                                                                                                </p>
                                                                                                <p>
                                                                                                    <strong>422:</strong>
                                                                                                    This basically means that the API heard your call but it didn’t like something in the request body.
                                                                                                </p>
                                                                                                <ul>
                                                                                                    <li>
                                                                                                        The format of a field may be wrong, for example, text for a number field or an invalid date format (dates must be in this format: <code>2023-01-31</code>
                                                                                                        ).
                                                                                                    </li>
                                                                                                </ul>
                                                                                                <p>
                                                                                                    <strong>500:</strong>
                                                                                                    This may mean that your URLs are wrong, especially, you may have the wrong URL for OAuth authentication, such as you forget to add the path <code>/oauth/token</code>
                                                                                                    .
                                                                                                </p>
                                                                                                <p>Note that fields names are case sensitive. This will not cause an error in the API call, but the values will not be passed to the workflow properly and you will not see the values in the workflow forms.</p>
                                                                                            </blockquote>
                                                                                            <p>If you’ve gotten to here, your integration with SAP Build Process Automation is working!!</p>
                                                                                            <p>You can go into the SAP Build Process Automation monitoring and see there the process you just triggered, and check the context to make sure the parameters were sent properly.</p>
                                                                                            <div class="img-zoom img-zoom__hidden">
                                                                                                <div class="enlarge-icon">
                                                                                                    <svg width="40px" height="40px" viewBox="0 0 40 40" version="1.1" xmlns="http://www.w3.org/2000/svg">
                                                                                                        <g id="Atoms/Icons/Enlarge" stroke="none" stroke-width="1" fill="none" fill-rule="evenodd">
                                                                                                            <rect id="Rectangle" fill="#E9E9E9" opacity="0.8" x="0" y="0" width="40" height="40" rx="4"></rect>
                                                                                                            <g id="enlarge-icon" transform="translate(8.000000, 8.000000)" fill="#000000" fill-rule="nonzero">
                                                                                                                <polygon id="Path" points="24 0 14.25 0 18 3.75 13.5 8.25 15.75 10.5 20.25 6 24 9.75"></polygon>
                                                                                                                <polygon id="Path" points="24 24 24 14.25 20.25 18 15.75 13.5 13.5 15.75 18 20.25 14.25 24"></polygon>
                                                                                                                <polygon id="Path" points="0 24 9.75 24 6 20.25 10.5 15.75 8.25 13.5 3.75 18 0 14.25"></polygon>
                                                                                                                <polygon id="Path" points="0 0 0 9.75 3.75 6 8.25 10.5 10.5 8.25 6 3.75 9.75 0"></polygon>
                                                                                                            </g>
                                                                                                        </g>
                                                                                                    </svg>
                                                                                                </div>
                                                                                                <img src="/tutorials/build-apps-workflow-trigger/_jcr_content.github-proxy.1678009502.file/test-spa.png" alt="Process automation test"/>
                                                                                            </div>
                                                                                            <p>You can also check the Inbox to see the forms were created and the values properly passed into the workflow.</p>
                                                                                            <div class="img-zoom img-zoom__hidden">
                                                                                                <div class="enlarge-icon">
                                                                                                    <svg width="40px" height="40px" viewBox="0 0 40 40" version="1.1" xmlns="http://www.w3.org/2000/svg">
                                                                                                        <g id="Atoms/Icons/Enlarge" stroke="none" stroke-width="1" fill="none" fill-rule="evenodd">
                                                                                                            <rect id="Rectangle" fill="#E9E9E9" opacity="0.8" x="0" y="0" width="40" height="40" rx="4"></rect>
                                                                                                            <g id="enlarge-icon" transform="translate(8.000000, 8.000000)" fill="#000000" fill-rule="nonzero">
                                                                                                                <polygon id="Path" points="24 0 14.25 0 18 3.75 13.5 8.25 15.75 10.5 20.25 6 24 9.75"></polygon>
                                                                                                                <polygon id="Path" points="24 24 24 14.25 20.25 18 15.75 13.5 13.5 15.75 18 20.25 14.25 24"></polygon>
                                                                                                                <polygon id="Path" points="0 24 9.75 24 6 20.25 10.5 15.75 8.25 13.5 3.75 18 0 14.25"></polygon>
                                                                                                                <polygon id="Path" points="0 0 0 9.75 3.75 6 8.25 10.5 10.5 8.25 6 3.75 9.75 0"></polygon>
                                                                                                            </g>
                                                                                                        </g>
                                                                                                    </svg>
                                                                                                </div>
                                                                                                <img src="/tutorials/build-apps-workflow-trigger/_jcr_content.github-proxy.1678009502.file/test-inbox.png" alt="Inbox"/>
                                                                                            </div>
                                                                                        </div>
                                                                                        <div class="SubmitButton__root--QWQTU">
                                                                                            <span>
                                                                                                <a href="/bin/fiji/es/login.sapdxdevs.html" title="Log in">Log in</a>
                                                                                                to complete tutorial
                                                                                            </span>
                                                                                            <button disabled="" class="SubmitButton__button--I7eWM SubmitButton__disabled--V-NkW">Done</button>
                                                                                        </div>
                                                                                    </div>
                                                                                </div>
                                                                            </div>
                                                                        </div>
                                                                    </div>
                                                                </li>
                                                                <li id="4dd3d150-a801-4341-b766-7a2eaf811c71" class="Accordion__item--DNzPY">
                                                                    <div class="Expander__expander--4DOyC">
                                                                        <div class="Top__top--kjtjD">
                                                                            <div class="Top__type--CI8yu">
                                                                                <span class="Status__status--ucVFH Top__chained--TywwF">
                                                                                    <svg width="20" height="20" viewBox="0 0 20 20" fill="none" xmlns="http://www.w3.org/2000/svg">
                                                                                        <circle cx="10" cy="10" r="9.5" fill="#EAEBEE" stroke="#B1B1B1"></circle>
                                                                                    </svg>
                                                                                </span>
                                                                                <span class="Top__title--BIOWY">Step 6</span>
                                                                            </div>
                                                                            <button class="ExpanderButton__expanderButton--2JY9n" title="Collapse content" aria-label="Toggle accordion">
                                                                                <svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                                                                                    <path fill-rule="evenodd" clip-rule="evenodd" d="M2.40474 12.0001H21.4744H2.40474Z" fill="#003283"></path>
                                                                                    <path d="M2.40474 12.0001H21.4744" stroke="#085CAF" stroke-width="3" stroke-linecap="round" stroke-linejoin="round"></path>
                                                                                    <path fill-rule="evenodd" clip-rule="evenodd" d="M11.9401 2.40767L11.9401 21.5942L11.9401 2.40767Z" fill="#003283"></path>
                                                                                    <path d="M11.9401 2.40767L11.9401 21.5942" stroke="#085CAF" stroke-width="3" stroke-linecap="round" stroke-linejoin="round"></path>
                                                                                </svg>
                                                                            </button>
                                                                        </div>
                                                                        <div class="Header__bottom--mSn+X">
                                                                            <div>
                                                                                <button class="Header__title--W0rcU">
                                                                                    <span class="Header__url--+cB+Z Header__linked--TcvJ0">Create data variable</span>
                                                                                </button>
                                                                                <div class="Header__wrapper--XNMcL"></div>
                                                                            </div>
                                                                        </div>
                                                                        <div class="Expander__wrapper--GK6+l">
                                                                            <div class="Expander__hide--Q-ULJ">
                                                                                <div class="Expander__separator--dU1cP"></div>
                                                                                <div>
                                                                                    <div>
                                                                                        <div class="tutorialBody">
                                                                                            <ol>
                                                                                                <li>
                                                                                                    <p>
                                                                                                        Back on the UI canvas, select <strong>Variables</strong>
                                                                                                        .
                                                                                                    </p>
                                                                                                </li>
                                                                                                <li>
                                                                                                    <p>
                                                                                                        On the left, click <strong>Data Variables</strong>
                                                                                                        .
                                                                                                    </p>
                                                                                                </li>
                                                                                                <li>
                                                                                                    <p>
                                                                                                        Click <strong>Add Data Variable</strong>
                                                                                                        , and choose <strong>Trigger Workflow</strong>
                                                                                                        as the data resource on which to base the data variable.
                                                                                                    </p>
                                                                                                    <blockquote>
                                                                                                        <p>The schema of the data variable will be the same as the data resource.</p>
                                                                                                    </blockquote>
                                                                                                    <div class="img-zoom img-zoom__hidden">
                                                                                                        <div class="enlarge-icon">
                                                                                                            <svg width="40px" height="40px" viewBox="0 0 40 40" version="1.1" xmlns="http://www.w3.org/2000/svg">
                                                                                                                <g id="Atoms/Icons/Enlarge" stroke="none" stroke-width="1" fill="none" fill-rule="evenodd">
                                                                                                                    <rect id="Rectangle" fill="#E9E9E9" opacity="0.8" x="0" y="0" width="40" height="40" rx="4"></rect>
                                                                                                                    <g id="enlarge-icon" transform="translate(8.000000, 8.000000)" fill="#000000" fill-rule="nonzero">
                                                                                                                        <polygon id="Path" points="24 0 14.25 0 18 3.75 13.5 8.25 15.75 10.5 20.25 6 24 9.75"></polygon>
                                                                                                                        <polygon id="Path" points="24 24 24 14.25 20.25 18 15.75 13.5 13.5 15.75 18 20.25 14.25 24"></polygon>
                                                                                                                        <polygon id="Path" points="0 24 9.75 24 6 20.25 10.5 15.75 8.25 13.5 3.75 18 0 14.25"></polygon>
                                                                                                                        <polygon id="Path" points="0 0 0 9.75 3.75 6 8.25 10.5 10.5 8.25 6 3.75 9.75 0"></polygon>
                                                                                                                    </g>
                                                                                                                </g>
                                                                                                            </svg>
                                                                                                        </div>
                                                                                                        <img src="/tutorials/build-apps-workflow-trigger/_jcr_content.github-proxy.1678009502.file/data-variable-new.png" alt="New data variable"/>
                                                                                                    </div>
                                                                                                </li>
                                                                                                <li>
                                                                                                    <p>
                                                                                                        On the right, choose <strong>New data record</strong>
                                                                                                        .
                                                                                                    </p>
                                                                                                    <div class="img-zoom img-zoom__hidden">
                                                                                                        <div class="enlarge-icon">
                                                                                                            <svg width="40px" height="40px" viewBox="0 0 40 40" version="1.1" xmlns="http://www.w3.org/2000/svg">
                                                                                                                <g id="Atoms/Icons/Enlarge" stroke="none" stroke-width="1" fill="none" fill-rule="evenodd">
                                                                                                                    <rect id="Rectangle" fill="#E9E9E9" opacity="0.8" x="0" y="0" width="40" height="40" rx="4"></rect>
                                                                                                                    <g id="enlarge-icon" transform="translate(8.000000, 8.000000)" fill="#000000" fill-rule="nonzero">
                                                                                                                        <polygon id="Path" points="24 0 14.25 0 18 3.75 13.5 8.25 15.75 10.5 20.25 6 24 9.75"></polygon>
                                                                                                                        <polygon id="Path" points="24 24 24 14.25 20.25 18 15.75 13.5 13.5 15.75 18 20.25 14.25 24"></polygon>
                                                                                                                        <polygon id="Path" points="0 24 9.75 24 6 20.25 10.5 15.75 8.25 13.5 3.75 18 0 14.25"></polygon>
                                                                                                                        <polygon id="Path" points="0 0 0 9.75 3.75 6 8.25 10.5 10.5 8.25 6 3.75 9.75 0"></polygon>
                                                                                                                    </g>
                                                                                                                </g>
                                                                                                            </svg>
                                                                                                        </div>
                                                                                                        <img src="/tutorials/build-apps-workflow-trigger/_jcr_content.github-proxy.1678009502.file/data-variable-single.png" alt="New data record"/>
                                                                                                    </div>
                                                                                                </li>
                                                                                                <li>
                                                                                                    <p>
                                                                                                        Click <strong>Save</strong>
                                                                                                        (upper right).
                                                                                                    </p>
                                                                                                </li>
                                                                                            </ol>
                                                                                        </div>
                                                                                        <div class="SubmitButton__root--QWQTU">
                                                                                            <span>
                                                                                                <a href="/bin/fiji/es/login.sapdxdevs.html" title="Log in">Log in</a>
                                                                                                to complete tutorial
                                                                                            </span>
                                                                                            <button disabled="" class="SubmitButton__button--I7eWM SubmitButton__disabled--V-NkW">Done</button>
                                                                                        </div>
                                                                                    </div>
                                                                                </div>
                                                                            </div>
                                                                        </div>
                                                                    </div>
                                                                </li>
                                                                <li id="8a6e8b4b-ed38-4221-9b92-024467eb7011" class="Accordion__item--DNzPY">
                                                                    <div class="Expander__expander--4DOyC">
                                                                        <div class="Top__top--kjtjD">
                                                                            <div class="Top__type--CI8yu">
                                                                                <span class="Status__status--ucVFH Top__chained--TywwF">
                                                                                    <svg width="20" height="20" viewBox="0 0 20 20" fill="none" xmlns="http://www.w3.org/2000/svg">
                                                                                        <circle cx="10" cy="10" r="9.5" fill="#EAEBEE" stroke="#B1B1B1"></circle>
                                                                                    </svg>
                                                                                </span>
                                                                                <span class="Top__title--BIOWY">Step 7</span>
                                                                            </div>
                                                                            <button class="ExpanderButton__expanderButton--2JY9n" title="Collapse content" aria-label="Toggle accordion">
                                                                                <svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                                                                                    <path fill-rule="evenodd" clip-rule="evenodd" d="M2.40474 12.0001H21.4744H2.40474Z" fill="#003283"></path>
                                                                                    <path d="M2.40474 12.0001H21.4744" stroke="#085CAF" stroke-width="3" stroke-linecap="round" stroke-linejoin="round"></path>
                                                                                    <path fill-rule="evenodd" clip-rule="evenodd" d="M11.9401 2.40767L11.9401 21.5942L11.9401 2.40767Z" fill="#003283"></path>
                                                                                    <path d="M11.9401 2.40767L11.9401 21.5942" stroke="#085CAF" stroke-width="3" stroke-linecap="round" stroke-linejoin="round"></path>
                                                                                </svg>
                                                                            </button>
                                                                        </div>
                                                                        <div class="Header__bottom--mSn+X">
                                                                            <div>
                                                                                <button class="Header__title--W0rcU">
                                                                                    <span class="Header__url--+cB+Z Header__linked--TcvJ0">Bind data variable to UI elements</span>
                                                                                </button>
                                                                                <div class="Header__wrapper--XNMcL"></div>
                                                                            </div>
                                                                        </div>
                                                                        <div class="Expander__wrapper--GK6+l">
                                                                            <div class="Expander__hide--Q-ULJ">
                                                                                <div class="Expander__separator--dU1cP"></div>
                                                                                <div>
                                                                                    <div>
                                                                                        <div class="tutorialBody">
                                                                                            <ol>
                                                                                                <li>
                                                                                                    Go back to <strong>View</strong>
                                                                                                    so you can see the UI canvas.
                                                                                                </li>
                                                                                                <li>
                                                                                                    Click on the first input field (for <strong>Customer</strong>
                                                                                                    ).

                                                                                                    <p>
                                                                                                        In the <strong>Properties</strong>
                                                                                                        tab, click the <strong>X</strong>
                                                                                                        next to the <strong>Value</strong>
                                                                                                        field, and select <strong>Data and Variables &gt;Data Variables &gt;Trigger Workflow1 &gt;shipToParty</strong>
                                                                                                        .
                                                                                                    </p>
                                                                                                    <div class="img-zoom img-zoom__hidden">
                                                                                                        <div class="enlarge-icon">
                                                                                                            <svg width="40px" height="40px" viewBox="0 0 40 40" version="1.1" xmlns="http://www.w3.org/2000/svg">
                                                                                                                <g id="Atoms/Icons/Enlarge" stroke="none" stroke-width="1" fill="none" fill-rule="evenodd">
                                                                                                                    <rect id="Rectangle" fill="#E9E9E9" opacity="0.8" x="0" y="0" width="40" height="40" rx="4"></rect>
                                                                                                                    <g id="enlarge-icon" transform="translate(8.000000, 8.000000)" fill="#000000" fill-rule="nonzero">
                                                                                                                        <polygon id="Path" points="24 0 14.25 0 18 3.75 13.5 8.25 15.75 10.5 20.25 6 24 9.75"></polygon>
                                                                                                                        <polygon id="Path" points="24 24 24 14.25 20.25 18 15.75 13.5 13.5 15.75 18 20.25 14.25 24"></polygon>
                                                                                                                        <polygon id="Path" points="0 24 9.75 24 6 20.25 10.5 15.75 8.25 13.5 3.75 18 0 14.25"></polygon>
                                                                                                                        <polygon id="Path" points="0 0 0 9.75 3.75 6 8.25 10.5 10.5 8.25 6 3.75 9.75 0"></polygon>
                                                                                                                    </g>
                                                                                                                </g>
                                                                                                            </svg>
                                                                                                        </div>
                                                                                                        <img src="/tutorials/build-apps-workflow-trigger/_jcr_content.github-proxy.1678009502.file/bind-input1.png" alt="Binding input field"/>
                                                                                                    </div>
                                                                                                    <p>
                                                                                                        Click <strong>Save</strong>
                                                                                                    </p>
                                                                                                </li>
                                                                                                <li>
                                                                                                    <p>
                                                                                                        Click on the second input field (for <strong>Material</strong>
                                                                                                        ).
                                                                                                    </p>
                                                                                                    <p>
                                                                                                        In the <strong>Properties</strong>
                                                                                                        tab, click the <strong>X</strong>
                                                                                                        next to the <strong>Value</strong>
                                                                                                        field, and select <strong>Data and Variables &gt;Data Variables &gt;Trigger Workflow1 &gt;material</strong>
                                                                                                        .
                                                                                                    </p>
                                                                                                    <p>
                                                                                                        Click <strong>Save</strong>
                                                                                                    </p>
                                                                                                </li>
                                                                                                <li>
                                                                                                    <p>
                                                                                                        Click on the third input field (for <strong>Amount</strong>
                                                                                                        ).
                                                                                                    </p>
                                                                                                    <p>
                                                                                                        In the <strong>Properties</strong>
                                                                                                        tab, click the <strong>X</strong>
                                                                                                        next to the <strong>Value</strong>
                                                                                                        field, and select <strong>Data and Variables &gt;Data Variables &gt;Trigger Workflow1 &gt;orderAmount</strong>
                                                                                                        .
                                                                                                    </p>
                                                                                                    <p>
                                                                                                        Click <strong>Save</strong>
                                                                                                    </p>
                                                                                                </li>
                                                                                                <li>
                                                                                                    <p>
                                                                                                        Click on the fourth input field (for <strong>Delivery Date</strong>
                                                                                                        ).
                                                                                                    </p>
                                                                                                    <p>
                                                                                                        In the <strong>Properties</strong>
                                                                                                        tab, click the <strong>X</strong>
                                                                                                        next to the <strong>Value</strong>
                                                                                                        field, and select <strong>Data and Variables &gt;Data Variables &gt;Trigger Workflow1 &gt;expectedDeliveryDate</strong>
                                                                                                        .
                                                                                                    </p>
                                                                                                    <p>
                                                                                                        Click <strong>Save</strong>
                                                                                                    </p>
                                                                                                </li>
                                                                                                <li>
                                                                                                    <p>
                                                                                                        Click <strong>Save</strong>
                                                                                                        (upper right).
                                                                                                    </p>
                                                                                                </li>
                                                                                            </ol>
                                                                                        </div>
                                                                                        <div class="SubmitButton__root--QWQTU">
                                                                                            <span>
                                                                                                <a href="/bin/fiji/es/login.sapdxdevs.html" title="Log in">Log in</a>
                                                                                                to complete tutorial
                                                                                            </span>
                                                                                            <button disabled="" class="SubmitButton__button--I7eWM SubmitButton__disabled--V-NkW">Done</button>
                                                                                        </div>
                                                                                    </div>
                                                                                </div>
                                                                            </div>
                                                                        </div>
                                                                    </div>
                                                                </li>
                                                                <li id="b9d12bd0-cc00-476e-b150-d78a0ef2e09f" class="Accordion__item--DNzPY">
                                                                    <div class="Expander__expander--4DOyC">
                                                                        <div class="Top__top--kjtjD">
                                                                            <div class="Top__type--CI8yu">
                                                                                <span class="Status__status--ucVFH Top__chained--TywwF">
                                                                                    <svg width="20" height="20" viewBox="0 0 20 20" fill="none" xmlns="http://www.w3.org/2000/svg">
                                                                                        <circle cx="10" cy="10" r="9.5" fill="#EAEBEE" stroke="#B1B1B1"></circle>
                                                                                    </svg>
                                                                                </span>
                                                                                <span class="Top__title--BIOWY">Step 8</span>
                                                                            </div>
                                                                            <button class="ExpanderButton__expanderButton--2JY9n" title="Collapse content" aria-label="Toggle accordion">
                                                                                <svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                                                                                    <path fill-rule="evenodd" clip-rule="evenodd" d="M2.40474 12.0001H21.4744H2.40474Z" fill="#003283"></path>
                                                                                    <path d="M2.40474 12.0001H21.4744" stroke="#085CAF" stroke-width="3" stroke-linecap="round" stroke-linejoin="round"></path>
                                                                                    <path fill-rule="evenodd" clip-rule="evenodd" d="M11.9401 2.40767L11.9401 21.5942L11.9401 2.40767Z" fill="#003283"></path>
                                                                                    <path d="M11.9401 2.40767L11.9401 21.5942" stroke="#085CAF" stroke-width="3" stroke-linecap="round" stroke-linejoin="round"></path>
                                                                                </svg>
                                                                            </button>
                                                                        </div>
                                                                        <div class="Header__bottom--mSn+X">
                                                                            <div>
                                                                                <button class="Header__title--W0rcU">
                                                                                    <span class="Header__url--+cB+Z Header__linked--TcvJ0">Add logic to trigger workflow</span>
                                                                                </button>
                                                                                <div class="Header__wrapper--XNMcL"></div>
                                                                            </div>
                                                                        </div>
                                                                        <div class="Expander__wrapper--GK6+l">
                                                                            <div class="Expander__hide--Q-ULJ">
                                                                                <div class="Expander__separator--dU1cP"></div>
                                                                                <div>
                                                                                    <div>
                                                                                        <div class="tutorialBody">
                                                                                            <ol>
                                                                                                <li>
                                                                                                    <p>
                                                                                                        Click on the <strong>Get Approval</strong>
                                                                                                        button, and open the logic canvas by clicking <strong>Add logic to Button1</strong>
                                                                                                        at the bottom right.
                                                                                                    </p>
                                                                                                    <div class="img-zoom img-zoom__hidden">
                                                                                                        <div class="enlarge-icon">
                                                                                                            <svg width="40px" height="40px" viewBox="0 0 40 40" version="1.1" xmlns="http://www.w3.org/2000/svg">
                                                                                                                <g id="Atoms/Icons/Enlarge" stroke="none" stroke-width="1" fill="none" fill-rule="evenodd">
                                                                                                                    <rect id="Rectangle" fill="#E9E9E9" opacity="0.8" x="0" y="0" width="40" height="40" rx="4"></rect>
                                                                                                                    <g id="enlarge-icon" transform="translate(8.000000, 8.000000)" fill="#000000" fill-rule="nonzero">
                                                                                                                        <polygon id="Path" points="24 0 14.25 0 18 3.75 13.5 8.25 15.75 10.5 20.25 6 24 9.75"></polygon>
                                                                                                                        <polygon id="Path" points="24 24 24 14.25 20.25 18 15.75 13.5 13.5 15.75 18 20.25 14.25 24"></polygon>
                                                                                                                        <polygon id="Path" points="0 24 9.75 24 6 20.25 10.5 15.75 8.25 13.5 3.75 18 0 14.25"></polygon>
                                                                                                                        <polygon id="Path" points="0 0 0 9.75 3.75 6 8.25 10.5 10.5 8.25 6 3.75 9.75 0"></polygon>
                                                                                                                    </g>
                                                                                                                </g>
                                                                                                            </svg>
                                                                                                        </div>
                                                                                                        <img src="/tutorials/build-apps-workflow-trigger/_jcr_content.github-proxy.1678009502.file/logic-open1.png" alt="Open logic canvas"/>
                                                                                                    </div>
                                                                                                </li>
                                                                                                <li>
                                                                                                    <p>
                                                                                                        Drag a <strong>Create record</strong>
                                                                                                        flow function onto the canvas, and connect the component tap event to it.
                                                                                                    </p>
                                                                                                    <div class="img-zoom img-zoom__hidden">
                                                                                                        <div class="enlarge-icon">
                                                                                                            <svg width="40px" height="40px" viewBox="0 0 40 40" version="1.1" xmlns="http://www.w3.org/2000/svg">
                                                                                                                <g id="Atoms/Icons/Enlarge" stroke="none" stroke-width="1" fill="none" fill-rule="evenodd">
                                                                                                                    <rect id="Rectangle" fill="#E9E9E9" opacity="0.8" x="0" y="0" width="40" height="40" rx="4"></rect>
                                                                                                                    <g id="enlarge-icon" transform="translate(8.000000, 8.000000)" fill="#000000" fill-rule="nonzero">
                                                                                                                        <polygon id="Path" points="24 0 14.25 0 18 3.75 13.5 8.25 15.75 10.5 20.25 6 24 9.75"></polygon>
                                                                                                                        <polygon id="Path" points="24 24 24 14.25 20.25 18 15.75 13.5 13.5 15.75 18 20.25 14.25 24"></polygon>
                                                                                                                        <polygon id="Path" points="0 24 9.75 24 6 20.25 10.5 15.75 8.25 13.5 3.75 18 0 14.25"></polygon>
                                                                                                                        <polygon id="Path" points="0 0 0 9.75 3.75 6 8.25 10.5 10.5 8.25 6 3.75 9.75 0"></polygon>
                                                                                                                    </g>
                                                                                                                </g>
                                                                                                            </svg>
                                                                                                        </div>
                                                                                                        <img src="/tutorials/build-apps-workflow-trigger/_jcr_content.github-proxy.1678009502.file/logic-create-record.png" alt="Create record"/>
                                                                                                    </div>
                                                                                                </li>
                                                                                                <li>
                                                                                                    <p>
                                                                                                        Click on the <strong>Create record</strong>
                                                                                                        flow function and configure it in the <strong>Properties</strong>
                                                                                                        pane on the right.
                                                                                                    </p>
                                                                                                    <p>
                                                                                                        For <strong>Resource name</strong>
                                                                                                        , this should already be set to <strong>Trigger Workflow</strong>
                                                                                                        , since you have only one data resource.
                                                                                                    </p>
                                                                                                    <div class="img-zoom img-zoom__hidden">
                                                                                                        <div class="enlarge-icon">
                                                                                                            <svg width="40px" height="40px" viewBox="0 0 40 40" version="1.1" xmlns="http://www.w3.org/2000/svg">
                                                                                                                <g id="Atoms/Icons/Enlarge" stroke="none" stroke-width="1" fill="none" fill-rule="evenodd">
                                                                                                                    <rect id="Rectangle" fill="#E9E9E9" opacity="0.8" x="0" y="0" width="40" height="40" rx="4"></rect>
                                                                                                                    <g id="enlarge-icon" transform="translate(8.000000, 8.000000)" fill="#000000" fill-rule="nonzero">
                                                                                                                        <polygon id="Path" points="24 0 14.25 0 18 3.75 13.5 8.25 15.75 10.5 20.25 6 24 9.75"></polygon>
                                                                                                                        <polygon id="Path" points="24 24 24 14.25 20.25 18 15.75 13.5 13.5 15.75 18 20.25 14.25 24"></polygon>
                                                                                                                        <polygon id="Path" points="0 24 9.75 24 6 20.25 10.5 15.75 8.25 13.5 3.75 18 0 14.25"></polygon>
                                                                                                                        <polygon id="Path" points="0 0 0 9.75 3.75 6 8.25 10.5 10.5 8.25 6 3.75 9.75 0"></polygon>
                                                                                                                    </g>
                                                                                                                </g>
                                                                                                            </svg>
                                                                                                        </div>
                                                                                                        <img src="/tutorials/build-apps-workflow-trigger/_jcr_content.github-proxy.1678009502.file/logic-create-record-binding.png" alt="Create record binding"/>
                                                                                                    </div>
                                                                                                    <p>
                                                                                                        For <strong>Record</strong>
                                                                                                        , you have to bind each of the data variable fields to the appropriate record field. 
                                                                                                    </p>
                                                                                                    <p>
                                                                                                        There are many ways to do binding. For <strong>Record</strong>
                                                                                                        , you will use a formula. Click on the object binding button:
                                                                                                    </p>
                                                                                                    <div class="img-zoom img-zoom__hidden">
                                                                                                        <div class="enlarge-icon">
                                                                                                            <svg width="40px" height="40px" viewBox="0 0 40 40" version="1.1" xmlns="http://www.w3.org/2000/svg">
                                                                                                                <g id="Atoms/Icons/Enlarge" stroke="none" stroke-width="1" fill="none" fill-rule="evenodd">
                                                                                                                    <rect id="Rectangle" fill="#E9E9E9" opacity="0.8" x="0" y="0" width="40" height="40" rx="4"></rect>
                                                                                                                    <g id="enlarge-icon" transform="translate(8.000000, 8.000000)" fill="#000000" fill-rule="nonzero">
                                                                                                                        <polygon id="Path" points="24 0 14.25 0 18 3.75 13.5 8.25 15.75 10.5 20.25 6 24 9.75"></polygon>
                                                                                                                        <polygon id="Path" points="24 24 24 14.25 20.25 18 15.75 13.5 13.5 15.75 18 20.25 14.25 24"></polygon>
                                                                                                                        <polygon id="Path" points="0 24 9.75 24 6 20.25 10.5 15.75 8.25 13.5 3.75 18 0 14.25"></polygon>
                                                                                                                        <polygon id="Path" points="0 0 0 9.75 3.75 6 8.25 10.5 10.5 8.25 6 3.75 9.75 0"></polygon>
                                                                                                                    </g>
                                                                                                                </g>
                                                                                                            </svg>
                                                                                                        </div>
                                                                                                        <img src="/tutorials/build-apps-workflow-trigger/_jcr_content.github-proxy.1678009502.file/objectbinding.png" alt="Object binding"/>
                                                                                                    </div>
                                                                                                    <p>
                                                                                                        Click <strong>Formula</strong>
                                                                                                        , then click on the existing formula, and replace it with the following:
                                                                                                    </p>
                                                                                                    <div class="code-header">
                                                                                                        <div class="language">JavaScript</div>
                                                                                                        <div class="copy">Copy</div>
                                                                                                    </div>
                                                                                                    <pre data-line="">
                                                                                                        <code class="line-numbers language-javascript">{salesorderdetails: {division: &quot;1010 &quot;, orderAmount: NUMBER(data[&quot;Trigger Workflow1 &quot;].salesorderdetails.orderAmount), shipToParty: data[&quot;Trigger Workflow1 &quot;].salesorderdetails.shipToParty, salesOrderType: &quot;OR &quot;, shippingCountry: &quot;Barbados &quot;, salesOrganisation: &quot;10 &quot;, distributionChannel: &quot;1000 &quot;, expectedDeliveryDate: data[&quot;Trigger Workflow1 &quot;].salesorderdetails.expectedDeliveryDate, material: data[&quot;Trigger Workflow1 &quot;].salesorderdetails.material}}
</code>
                                                                                                    </pre>
                                                                                                    <p>
                                                                                                        Click <strong>Save</strong>
                                                                                                        .
                                                                                                    </p>
                                                                                                    <blockquote>
                                                                                                        <p>
                                                                                                            <strong>What does the formula do?</strong>
                                                                                                        </p>
                                                                                                        <p>The 4 main fields we want to send should already be in our data variable, since we bound it to the input boxes. But we need to:</p>
                                                                                                        <ul>
                                                                                                            <li>Send values for some other fields.</li>
                                                                                                            <li>Format the number value for the order amount.</li>
                                                                                                            <li>Set the order date to today.</li>
                                                                                                        </ul>
                                                                                                        <p>
                                                                                                            You can do all this field by field – using the <strong>Object with properties</strong>
                                                                                                            binding – but to save time we gave you the formula.
                                                                                                        </p>
                                                                                                        <p>
                                                                                                            If you want to explore, open the binding for the <strong>Record</strong>
                                                                                                            field and select <strong>Object with properties</strong>
                                                                                                            and you can see the UI where you can set each field by hand.
                                                                                                        </p>
                                                                                                    </blockquote>
                                                                                                </li>
                                                                                                <li>
                                                                                                    <p>
                                                                                                        Drag a <strong>Toast</strong>
                                                                                                        flow function onto the canvas, and connect the <strong>top</strong>
                                                                                                        output of the <strong>Create record</strong>
                                                                                                        flow function to it.
                                                                                                    </p>
                                                                                                    <div class="img-zoom img-zoom__hidden">
                                                                                                        <div class="enlarge-icon">
                                                                                                            <svg width="40px" height="40px" viewBox="0 0 40 40" version="1.1" xmlns="http://www.w3.org/2000/svg">
                                                                                                                <g id="Atoms/Icons/Enlarge" stroke="none" stroke-width="1" fill="none" fill-rule="evenodd">
                                                                                                                    <rect id="Rectangle" fill="#E9E9E9" opacity="0.8" x="0" y="0" width="40" height="40" rx="4"></rect>
                                                                                                                    <g id="enlarge-icon" transform="translate(8.000000, 8.000000)" fill="#000000" fill-rule="nonzero">
                                                                                                                        <polygon id="Path" points="24 0 14.25 0 18 3.75 13.5 8.25 15.75 10.5 20.25 6 24 9.75"></polygon>
                                                                                                                        <polygon id="Path" points="24 24 24 14.25 20.25 18 15.75 13.5 13.5 15.75 18 20.25 14.25 24"></polygon>
                                                                                                                        <polygon id="Path" points="0 24 9.75 24 6 20.25 10.5 15.75 8.25 13.5 3.75 18 0 14.25"></polygon>
                                                                                                                        <polygon id="Path" points="0 0 0 9.75 3.75 6 8.25 10.5 10.5 8.25 6 3.75 9.75 0"></polygon>
                                                                                                                    </g>
                                                                                                                </g>
                                                                                                            </svg>
                                                                                                        </div>
                                                                                                        <img src="/tutorials/build-apps-workflow-trigger/_jcr_content.github-proxy.1678009502.file/bind-toast.png" alt="Toast"/>
                                                                                                    </div>
                                                                                                </li>
                                                                                                <li>
                                                                                                    <p>
                                                                                                        Click on the <strong>Toast</strong>
                                                                                                        flow function and configure it in the <strong>Properties</strong>
                                                                                                        pane on the right.
                                                                                                    </p>
                                                                                                    <p>
                                                                                                        For <strong>Toast message</strong>
                                                                                                        , click on the <strong>ABC</strong>
                                                                                                        , and then select <strong>Formula &gt;Formula</strong>
                                                                                                        .
                                                                                                    </p>
                                                                                                    <p>Erase the quotation marks, and enter the following formula:</p>
                                                                                                    <div class="code-header">
                                                                                                        <div class="language">JavaScript</div>
                                                                                                        <div class="copy">Copy</div>
                                                                                                    </div>
                                                                                                    <pre data-line="">
                                                                                                        <code class="line-numbers language-javascript">&quot;Triggered process with ID: &quot;+ outputs[&quot;Create record &quot;].response.id
</code>
                                                                                                    </pre>
                                                                                                    <p>
                                                                                                        Click <strong>Save</strong>
                                                                                                        .
                                                                                                    </p>
                                                                                                </li>
                                                                                                <li>
                                                                                                    <p>
                                                                                                        Click <strong>Save</strong>
                                                                                                        (upper right).
                                                                                                    </p>
                                                                                                </li>
                                                                                            </ol>
                                                                                        </div>
                                                                                        <div class="Validation__validation--qIF0R">
                                                                                            <h3 class="Validation__question--4UdN7">To what do you add flow functions so you can indicate what happens when a user takes an action, like clicking a button?</h3>
                                                                                            <ul class="Quiz__quiz--Fnjdc">
                                                                                                <li class="Answer__answer--XHMXB">
                                                                                                    <label class="Answer__label--YJCz1" for="80">
                                                                                                        Data tab<input type="radio" id="80" name="quiz8"/>
                                                                                                        <span class="Answer__checkMark--8pEzC Answer__checkMarkRadio--oUca+"></span>
                                                                                                    </label>
                                                                                                </li>
                                                                                                <li class="Answer__answer--XHMXB">
                                                                                                    <label class="Answer__label--YJCz1" for="81">
                                                                                                        Navigation tab<input type="radio" id="81" name="quiz8"/>
                                                                                                        <span class="Answer__checkMark--8pEzC Answer__checkMarkRadio--oUca+"></span>
                                                                                                    </label>
                                                                                                </li>
                                                                                                <li class="Answer__answer--XHMXB">
                                                                                                    <label class="Answer__label--YJCz1" for="82">
                                                                                                        Auth tab<input type="radio" id="82" name="quiz8"/>
                                                                                                        <span class="Answer__checkMark--8pEzC Answer__checkMarkRadio--oUca+"></span>
                                                                                                    </label>
                                                                                                </li>
                                                                                                <li class="Answer__answer--XHMXB">
                                                                                                    <label class="Answer__label--YJCz1" for="83">
                                                                                                        Logic canvas<input type="radio" id="83" name="quiz8"/>
                                                                                                        <span class="Answer__checkMark--8pEzC Answer__checkMarkRadio--oUca+"></span>
                                                                                                    </label>
                                                                                                </li>
                                                                                                <li class="Answer__answer--XHMXB">
                                                                                                    <label class="Answer__label--YJCz1" for="84">
                                                                                                        Properties tab<input type="radio" id="84" name="quiz8"/>
                                                                                                        <span class="Answer__checkMark--8pEzC Answer__checkMarkRadio--oUca+"></span>
                                                                                                    </label>
                                                                                                </li>
                                                                                                <li class="Answer__answer--XHMXB">
                                                                                                    <label class="Answer__label--YJCz1" for="85">
                                                                                                        JavaScript tab<input type="radio" id="85" name="quiz8"/>
                                                                                                        <span class="Answer__checkMark--8pEzC Answer__checkMarkRadio--oUca+"></span>
                                                                                                    </label>
                                                                                                </li>
                                                                                            </ul>
                                                                                            <div class="SubmitButton__root--QWQTU">
                                                                                                <span>
                                                                                                    <a href="/bin/fiji/es/login.sapdxdevs.html" title="Log in">Log in</a>
                                                                                                    to complete tutorial
                                                                                                </span>
                                                                                                <button disabled="" class="SubmitButton__button--I7eWM SubmitButton__disabled--V-NkW">Check answer</button>
                                                                                            </div>
                                                                                        </div>
                                                                                    </div>
                                                                                </div>
                                                                            </div>
                                                                        </div>
                                                                    </div>
                                                                </li>
                                                                <li id="39ceebec-a77e-4221-8b38-7c6aa6ff72fe" class="Accordion__item--DNzPY">
                                                                    <div class="Expander__expander--4DOyC">
                                                                        <div class="Top__top--kjtjD">
                                                                            <div class="Top__type--CI8yu">
                                                                                <span class="Status__status--ucVFH Top__chained--TywwF">
                                                                                    <svg width="20" height="20" viewBox="0 0 20 20" fill="none" xmlns="http://www.w3.org/2000/svg">
                                                                                        <circle cx="10" cy="10" r="9.5" fill="#EAEBEE" stroke="#B1B1B1"></circle>
                                                                                    </svg>
                                                                                </span>
                                                                                <span class="Top__title--BIOWY">Step 9</span>
                                                                            </div>
                                                                            <button class="ExpanderButton__expanderButton--2JY9n" title="Collapse content" aria-label="Toggle accordion">
                                                                                <svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                                                                                    <path fill-rule="evenodd" clip-rule="evenodd" d="M2.40474 12.0001H21.4744H2.40474Z" fill="#003283"></path>
                                                                                    <path d="M2.40474 12.0001H21.4744" stroke="#085CAF" stroke-width="3" stroke-linecap="round" stroke-linejoin="round"></path>
                                                                                    <path fill-rule="evenodd" clip-rule="evenodd" d="M11.9401 2.40767L11.9401 21.5942L11.9401 2.40767Z" fill="#003283"></path>
                                                                                    <path d="M11.9401 2.40767L11.9401 21.5942" stroke="#085CAF" stroke-width="3" stroke-linecap="round" stroke-linejoin="round"></path>
                                                                                </svg>
                                                                            </button>
                                                                        </div>
                                                                        <div class="Header__bottom--mSn+X">
                                                                            <div>
                                                                                <button class="Header__title--W0rcU">
                                                                                    <span class="Header__url--+cB+Z Header__linked--TcvJ0">Run app</span>
                                                                                </button>
                                                                                <div class="Header__wrapper--XNMcL"></div>
                                                                            </div>
                                                                        </div>
                                                                        <div class="Expander__wrapper--GK6+l">
                                                                            <div class="Expander__hide--Q-ULJ">
                                                                                <div class="Expander__separator--dU1cP"></div>
                                                                                <div>
                                                                                    <div>
                                                                                        <div class="tutorialBody">
                                                                                            <ol>
                                                                                                <li>
                                                                                                    <p>
                                                                                                        Click the <strong>Launch</strong>
                                                                                                        tab, and then <strong>Open Preview Portal</strong>
                                                                                                        .
                                                                                                    </p>
                                                                                                    <div class="img-zoom img-zoom__hidden">
                                                                                                        <div class="enlarge-icon">
                                                                                                            <svg width="40px" height="40px" viewBox="0 0 40 40" version="1.1" xmlns="http://www.w3.org/2000/svg">
                                                                                                                <g id="Atoms/Icons/Enlarge" stroke="none" stroke-width="1" fill="none" fill-rule="evenodd">
                                                                                                                    <rect id="Rectangle" fill="#E9E9E9" opacity="0.8" x="0" y="0" width="40" height="40" rx="4"></rect>
                                                                                                                    <g id="enlarge-icon" transform="translate(8.000000, 8.000000)" fill="#000000" fill-rule="nonzero">
                                                                                                                        <polygon id="Path" points="24 0 14.25 0 18 3.75 13.5 8.25 15.75 10.5 20.25 6 24 9.75"></polygon>
                                                                                                                        <polygon id="Path" points="24 24 24 14.25 20.25 18 15.75 13.5 13.5 15.75 18 20.25 14.25 24"></polygon>
                                                                                                                        <polygon id="Path" points="0 24 9.75 24 6 20.25 10.5 15.75 8.25 13.5 3.75 18 0 14.25"></polygon>
                                                                                                                        <polygon id="Path" points="0 0 0 9.75 3.75 6 8.25 10.5 10.5 8.25 6 3.75 9.75 0"></polygon>
                                                                                                                    </g>
                                                                                                                </g>
                                                                                                            </svg>
                                                                                                        </div>
                                                                                                        <img src="/tutorials/build-apps-workflow-trigger/_jcr_content.github-proxy.1678009502.file/launch.png" alt="Launch"/>
                                                                                                    </div>
                                                                                                </li>
                                                                                                <li>
                                                                                                    <p>
                                                                                                        Click <strong>Open web preview</strong>
                                                                                                        (left).
                                                                                                    </p>
                                                                                                </li>
                                                                                                <li>
                                                                                                    <p>
                                                                                                        Select your project, <strong>Select Order Trigger</strong>
                                                                                                        .
                                                                                                    </p>
                                                                                                    <div class="img-zoom img-zoom__hidden">
                                                                                                        <div class="enlarge-icon">
                                                                                                            <svg width="40px" height="40px" viewBox="0 0 40 40" version="1.1" xmlns="http://www.w3.org/2000/svg">
                                                                                                                <g id="Atoms/Icons/Enlarge" stroke="none" stroke-width="1" fill="none" fill-rule="evenodd">
                                                                                                                    <rect id="Rectangle" fill="#E9E9E9" opacity="0.8" x="0" y="0" width="40" height="40" rx="4"></rect>
                                                                                                                    <g id="enlarge-icon" transform="translate(8.000000, 8.000000)" fill="#000000" fill-rule="nonzero">
                                                                                                                        <polygon id="Path" points="24 0 14.25 0 18 3.75 13.5 8.25 15.75 10.5 20.25 6 24 9.75"></polygon>
                                                                                                                        <polygon id="Path" points="24 24 24 14.25 20.25 18 15.75 13.5 13.5 15.75 18 20.25 14.25 24"></polygon>
                                                                                                                        <polygon id="Path" points="0 24 9.75 24 6 20.25 10.5 15.75 8.25 13.5 3.75 18 0 14.25"></polygon>
                                                                                                                        <polygon id="Path" points="0 0 0 9.75 3.75 6 8.25 10.5 10.5 8.25 6 3.75 9.75 0"></polygon>
                                                                                                                    </g>
                                                                                                                </g>
                                                                                                            </svg>
                                                                                                        </div>
                                                                                                        <img src="/tutorials/build-apps-workflow-trigger/_jcr_content.github-proxy.1678009502.file/launch-preview.png" alt="Launch preview"/>
                                                                                                    </div>
                                                                                                </li>
                                                                                                <li>
                                                                                                    <p>Enter the following values in your form:</p>
                                                                                                    <table>
                                                                                                        <thead>
                                                                                                            <tr>
                                                                                                                <th>Field </th>
                                                                                                                <th>Value </th>
                                                                                                            </tr>
                                                                                                        </thead>
                                                                                                        <tbody>
                                                                                                            <tr>
                                                                                                                <td>Customer </td>
                                                                                                                <td>
                                                                                                                    <code>Joe &#x27;s Bikes</code>
                                                                                                                </td>
                                                                                                            </tr>
                                                                                                            <tr>
                                                                                                                <td>Material </td>
                                                                                                                <td>
                                                                                                                    <code>HT-1000</code>
                                                                                                                </td>
                                                                                                            </tr>
                                                                                                            <tr>
                                                                                                                <td>Amount </td>
                                                                                                                <td>
                                                                                                                    <code>1000</code>
                                                                                                                </td>
                                                                                                            </tr>
                                                                                                            <tr>
                                                                                                                <td>Delivery Date </td>
                                                                                                                <td>
                                                                                                                    <code>2023-03-31</code>
                                                                                                                </td>
                                                                                                            </tr>
                                                                                                        </tbody>
                                                                                                    </table>
                                                                                                    <p>For the remaining fields, enter what you’d like.</p>
                                                                                                </li>
                                                                                                <li>
                                                                                                    <p>
                                                                                                        Click <strong>Get Approval</strong>
                                                                                                        .
                                                                                                    </p>
                                                                                                </li>
                                                                                            </ol>
                                                                                            <p>You process should be triggered and require approval (since the amount is 1000 or above).</p>
                                                                                            <p>You should see the toast message indicating the workflow was triggered, and with the process instance ID.</p>
                                                                                            <div class="img-zoom img-zoom__hidden">
                                                                                                <div class="enlarge-icon">
                                                                                                    <svg width="40px" height="40px" viewBox="0 0 40 40" version="1.1" xmlns="http://www.w3.org/2000/svg">
                                                                                                        <g id="Atoms/Icons/Enlarge" stroke="none" stroke-width="1" fill="none" fill-rule="evenodd">
                                                                                                            <rect id="Rectangle" fill="#E9E9E9" opacity="0.8" x="0" y="0" width="40" height="40" rx="4"></rect>
                                                                                                            <g id="enlarge-icon" transform="translate(8.000000, 8.000000)" fill="#000000" fill-rule="nonzero">
                                                                                                                <polygon id="Path" points="24 0 14.25 0 18 3.75 13.5 8.25 15.75 10.5 20.25 6 24 9.75"></polygon>
                                                                                                                <polygon id="Path" points="24 24 24 14.25 20.25 18 15.75 13.5 13.5 15.75 18 20.25 14.25 24"></polygon>
                                                                                                                <polygon id="Path" points="0 24 9.75 24 6 20.25 10.5 15.75 8.25 13.5 3.75 18 0 14.25"></polygon>
                                                                                                                <polygon id="Path" points="0 0 0 9.75 3.75 6 8.25 10.5 10.5 8.25 6 3.75 9.75 0"></polygon>
                                                                                                            </g>
                                                                                                        </g>
                                                                                                    </svg>
                                                                                                </div>
                                                                                                <img src="/tutorials/build-apps-workflow-trigger/_jcr_content.github-proxy.1678009502.file/launch-toast.png" alt="Preview toast"/>
                                                                                            </div>
                                                                                            <p>You can also see the results of the call in SAP Build Process Automation.</p>
                                                                                            <p>
                                                                                                Go to the <strong>Monitor</strong>
                                                                                                tab, then <strong>Process and Workflow Instances</strong>
                                                                                                . The first one should be the one you just triggered.
                                                                                            </p>
                                                                                            <ul>
                                                                                                <li>You can see the new process instance.</li>
                                                                                                <li>You can see the context, which is the values sent with the API.</li>
                                                                                                <li>You can also see the execution log, which in this case ran the auto-approve task because the amount was below 100000.</li>
                                                                                            </ul>
                                                                                            <p>The context field in yellow are the ones that you entered via the UI.</p>
                                                                                            <div class="img-zoom img-zoom__hidden">
                                                                                                <div class="enlarge-icon">
                                                                                                    <svg width="40px" height="40px" viewBox="0 0 40 40" version="1.1" xmlns="http://www.w3.org/2000/svg">
                                                                                                        <g id="Atoms/Icons/Enlarge" stroke="none" stroke-width="1" fill="none" fill-rule="evenodd">
                                                                                                            <rect id="Rectangle" fill="#E9E9E9" opacity="0.8" x="0" y="0" width="40" height="40" rx="4"></rect>
                                                                                                            <g id="enlarge-icon" transform="translate(8.000000, 8.000000)" fill="#000000" fill-rule="nonzero">
                                                                                                                <polygon id="Path" points="24 0 14.25 0 18 3.75 13.5 8.25 15.75 10.5 20.25 6 24 9.75"></polygon>
                                                                                                                <polygon id="Path" points="24 24 24 14.25 20.25 18 15.75 13.5 13.5 15.75 18 20.25 14.25 24"></polygon>
                                                                                                                <polygon id="Path" points="0 24 9.75 24 6 20.25 10.5 15.75 8.25 13.5 3.75 18 0 14.25"></polygon>
                                                                                                                <polygon id="Path" points="0 0 0 9.75 3.75 6 8.25 10.5 10.5 8.25 6 3.75 9.75 0"></polygon>
                                                                                                            </g>
                                                                                                        </g>
                                                                                                    </svg>
                                                                                                </div>
                                                                                                <img src="/tutorials/build-apps-workflow-trigger/_jcr_content.github-proxy.1678009502.file/launch-preview-SPA.png" alt="Preview in process automation"/>
                                                                                            </div>
                                                                                            <p>You can also see that the process instance ID is the same: in the toast message and in the upper right of the Monitor tab.</p>
                                                                                        </div>
                                                                                        <div class="Validation__validation--qIF0R">
                                                                                            <h3 class="Validation__question--4UdN7">In order to be able to use destinations to call the SAP Build Process Automation APIs, what do you need to enable?</h3>
                                                                                            <ul class="Quiz__quiz--Fnjdc">
                                                                                                <li class="Answer__answer--XHMXB">
                                                                                                    <label class="Answer__label--YJCz1" for="90">
                                                                                                        SAP BTP Integration Suite<input type="radio" id="90" name="quiz9"/>
                                                                                                        <span class="Answer__checkMark--8pEzC Answer__checkMarkRadio--oUca+"></span>
                                                                                                    </label>
                                                                                                </li>
                                                                                                <li class="Answer__answer--XHMXB">
                                                                                                    <label class="Answer__label--YJCz1" for="91">
                                                                                                        Debugging<input type="radio" id="91" name="quiz9"/>
                                                                                                        <span class="Answer__checkMark--8pEzC Answer__checkMarkRadio--oUca+"></span>
                                                                                                    </label>
                                                                                                </li>
                                                                                                <li class="Answer__answer--XHMXB">
                                                                                                    <label class="Answer__label--YJCz1" for="92">
                                                                                                        Navigation<input type="radio" id="92" name="quiz9"/>
                                                                                                        <span class="Answer__checkMark--8pEzC Answer__checkMarkRadio--oUca+"></span>
                                                                                                    </label>
                                                                                                </li>
                                                                                                <li class="Answer__answer--XHMXB">
                                                                                                    <label class="Answer__label--YJCz1" for="93">
                                                                                                        The logic pane <input type="radio" id="93" name="quiz9"/>
                                                                                                        <span class="Answer__checkMark--8pEzC Answer__checkMarkRadio--oUca+"></span>
                                                                                                    </label>
                                                                                                </li>
                                                                                                <li class="Answer__answer--XHMXB">
                                                                                                    <label class="Answer__label--YJCz1" for="94">
                                                                                                        Data variables <input type="radio" id="94" name="quiz9"/>
                                                                                                        <span class="Answer__checkMark--8pEzC Answer__checkMarkRadio--oUca+"></span>
                                                                                                    </label>
                                                                                                </li>
                                                                                                <li class="Answer__answer--XHMXB">
                                                                                                    <label class="Answer__label--YJCz1" for="95">
                                                                                                        SAP BTP authentication<input type="radio" id="95" name="quiz9"/>
                                                                                                        <span class="Answer__checkMark--8pEzC Answer__checkMarkRadio--oUca+"></span>
                                                                                                    </label>
                                                                                                </li>
                                                                                            </ul>
                                                                                            <div class="SubmitButton__root--QWQTU">
                                                                                                <span>
                                                                                                    <a href="/bin/fiji/es/login.sapdxdevs.html" title="Log in">Log in</a>
                                                                                                    to complete tutorial
                                                                                                </span>
                                                                                                <button disabled="" class="SubmitButton__button--I7eWM SubmitButton__disabled--V-NkW">Check answer</button>
                                                                                            </div>
                                                                                        </div>
                                                                                    </div>
                                                                                </div>
                                                                            </div>
                                                                        </div>
                                                                    </div>
                                                                </li>
                                                            </ul>
                                                        </div>
                                                    </div>
                                                    <div class="TutorialSideBar__tutorialSidebarWrapper--zGmyi">
                                                        <ul class="TutorialSideBar__steps--XS+ao">
                                                            <li class="TutorialSideBar__step--GzmaH">
                                                                <a class="step-id-bce79e08-36cb-45eb-8dbe-a83ae0a0ff8c" href="#bce79e08-36cb-45eb-8dbe-a83ae0a0ff8c">
                                                                    <div class="TutorialSideBar__stepNumber--dI0Y- " data-step="1"></div>
                                                                    <div class="TutorialSideBar__linkText--wG6k7" data-step-num="Step 1">Create a new app project</div>
                                                                </a>
                                                            </li>
                                                            <li class="TutorialSideBar__step--GzmaH">
                                                                <a class="step-id-92282e2c-3ad0-4796-9899-40e4ec2fe8eb" href="#92282e2c-3ad0-4796-9899-40e4ec2fe8eb">
                                                                    <div class="TutorialSideBar__stepNumber--dI0Y- " data-step="2"></div>
                                                                    <div class="TutorialSideBar__linkText--wG6k7" data-step-num="Step 2">Create the sales order page</div>
                                                                </a>
                                                            </li>
                                                            <li class="TutorialSideBar__step--GzmaH">
                                                                <a class="step-id-cd08140d-144e-4695-bae0-4cfd84f1aa7e" href="#cd08140d-144e-4695-bae0-4cfd84f1aa7e">
                                                                    <div class="TutorialSideBar__stepNumber--dI0Y- " data-step="3"></div>
                                                                    <div class="TutorialSideBar__linkText--wG6k7" data-step-num="Step 3">Enable SAP BTP authentication</div>
                                                                </a>
                                                            </li>
                                                            <li class="TutorialSideBar__step--GzmaH">
                                                                <a class="step-id-78aa568e-8deb-4bf0-9d16-b71146094511" href="#78aa568e-8deb-4bf0-9d16-b71146094511">
                                                                    <div class="TutorialSideBar__stepNumber--dI0Y- " data-step="4"></div>
                                                                    <div class="TutorialSideBar__linkText--wG6k7" data-step-num="Step 4">Create data resource to SAP Build Process Automation</div>
                                                                </a>
                                                            </li>
                                                            <li class="TutorialSideBar__step--GzmaH">
                                                                <a class="step-id-4be04d79-e6a0-43a1-874f-fdeb81f7cc61" href="#4be04d79-e6a0-43a1-874f-fdeb81f7cc61">
                                                                    <div class="TutorialSideBar__stepNumber--dI0Y- " data-step="5"></div>
                                                                    <div class="TutorialSideBar__linkText--wG6k7" data-step-num="Step 5">Test the trigger</div>
                                                                </a>
                                                            </li>
                                                            <li class="TutorialSideBar__step--GzmaH">
                                                                <a class="step-id-4dd3d150-a801-4341-b766-7a2eaf811c71" href="#4dd3d150-a801-4341-b766-7a2eaf811c71">
                                                                    <div class="TutorialSideBar__stepNumber--dI0Y- " data-step="6"></div>
                                                                    <div class="TutorialSideBar__linkText--wG6k7" data-step-num="Step 6">Create data variable</div>
                                                                </a>
                                                            </li>
                                                            <li class="TutorialSideBar__step--GzmaH">
                                                                <a class="step-id-8a6e8b4b-ed38-4221-9b92-024467eb7011" href="#8a6e8b4b-ed38-4221-9b92-024467eb7011">
                                                                    <div class="TutorialSideBar__stepNumber--dI0Y- " data-step="7"></div>
                                                                    <div class="TutorialSideBar__linkText--wG6k7" data-step-num="Step 7">Bind data variable to UI elements</div>
                                                                </a>
                                                            </li>
                                                            <li class="TutorialSideBar__step--GzmaH">
                                                                <a class="step-id-b9d12bd0-cc00-476e-b150-d78a0ef2e09f" href="#b9d12bd0-cc00-476e-b150-d78a0ef2e09f">
                                                                    <div class="TutorialSideBar__stepNumber--dI0Y- " data-step="8"></div>
                                                                    <div class="TutorialSideBar__linkText--wG6k7" data-step-num="Step 8">Add logic to trigger workflow</div>
                                                                </a>
                                                            </li>
                                                            <li class="TutorialSideBar__step--GzmaH">
                                                                <a class="step-id-39ceebec-a77e-4221-8b38-7c6aa6ff72fe" href="#39ceebec-a77e-4221-8b38-7c6aa6ff72fe">
                                                                    <div class="TutorialSideBar__stepNumber--dI0Y- " data-step="9"></div>
                                                                    <div class="TutorialSideBar__linkText--wG6k7" data-step-num="Step 9">Run app</div>
                                                                </a>
                                                            </li>
                                                        </ul>
                                                        <div class="TutorialSideBar__backToTopBtn--xNFhy">
                                                            <a href="#top">Back to Top</a>
                                                        </div>
                                                    </div>
                                                </section>
                                            </div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            <footer id="footer" class="footer-standard tier2" data-activity-map-region="Footer">
                <div class="aem-Grid aem-Grid--12 aem-Grid--default--12">
                    <div class="footer genericComponent parbase aem-GridColumn aem-GridColumn--default--12">
                        <div data-component="Footer" data-model="/bin/sapdxc/cache/footer/content/developers/website/languages/en/_jcr_content/parFooter/footer.model.json" data-mailto-link="https://developers.sap.com/tutorials/build-apps-workflow-trigger.html">
                            <!-- SDI include (path: /content/developers/website/languages/en/tutorials/build-apps-workflow-trigger/_jcr_content/parFooter/footer.cache.html, resourceType: sapdx/components/modular/nav/footer/footerSSR) -->
                            <div class="Footer__root--fhJyO fontBookBP Footer__tier2--jOYaD">
                                <div class="Grid__container--7X0ya">
                                    <div class="Grid__row--VKNKI ">
                                        <div class="Grid__col-12--7Dsx8 Grid__col-sm-4--ay-1g Grid__col-lg-3--Afzxx ">
                                            <div class="NavigationColumn__root--jheSe NavigationColumn__tier2--QdzMQ">
                                                <h3 class="NavigationColumn__title--3x2kD">
                                                    <button disabled="" class="NavigationColumn__accordionOpener--5HFJI fontMediumBP NavigationColumn__tier2--QdzMQ" aria-disabled="true" aria-expanded="false">
                                                        <span>Developer Products</span>
                                                    </button>
                                                </h3>
                                                <div>
                                                    <div>
                                                        <ul class="NavigationList__root--No5zo">
                                                            <li>
                                                                <a class="NavigationList__navigationLink--Icnc1 fontBookBP NavigationList__tier2--xVf7f" href="/topics/abap-platform.html" target="_self">ABAP Platform</a>
                                                            </li>
                                                            <li>
                                                                <a class="NavigationList__navigationLink--Icnc1 fontBookBP NavigationList__tier2--xVf7f" href="/topics/business-application-studio.html" target="_self">SAP Business Application Studio</a>
                                                            </li>
                                                            <li>
                                                                <a class="NavigationList__navigationLink--Icnc1 fontBookBP NavigationList__tier2--xVf7f" href="/topics/cloud-platform.html" target="_self">SAP Business Technology Platform</a>
                                                            </li>
                                                            <li>
                                                                <a class="NavigationList__navigationLink--Icnc1 fontBookBP NavigationList__tier2--xVf7f" href="/topics/conversational-ai.html" target="_self">SAP Conversational AI</a>
                                                            </li>
                                                            <li>
                                                                <a class="NavigationList__navigationLink--Icnc1 fontBookBP NavigationList__tier2--xVf7f" href="/topics/data-intelligence.html" target="_self">SAP Data Intelligence</a>
                                                            </li>
                                                            <li>
                                                                <a class="NavigationList__navigationLink--Icnc1 fontBookBP NavigationList__tier2--xVf7f" href="/topics/hana.html" target="_self">SAP HANA</a>
                                                            </li>
                                                            <li>
                                                                <a class="NavigationList__navigationLink--Icnc1 fontBookBP NavigationList__tier2--xVf7f" href="/topics.html" target="_self">All Products</a>
                                                            </li>
                                                        </ul>
                                                    </div>
                                                </div>
                                            </div>
                                        </div>
                                        <div class="Grid__col-12--7Dsx8 Grid__col-sm-4--ay-1g Grid__col-lg-3--Afzxx ">
                                            <div class="NavigationColumn__root--jheSe NavigationColumn__tier2--QdzMQ">
                                                <h3 class="NavigationColumn__title--3x2kD">
                                                    <button disabled="" class="NavigationColumn__accordionOpener--5HFJI fontMediumBP NavigationColumn__tier2--QdzMQ" aria-disabled="true" aria-expanded="false">
                                                        <span>Trials &amp;Downloads</span>
                                                    </button>
                                                </h3>
                                                <div>
                                                    <div>
                                                        <ul class="NavigationList__root--No5zo">
                                                            <li>
                                                                <a class="NavigationList__navigationLink--Icnc1 fontBookBP NavigationList__tier2--xVf7f" href="https://tools.eu1.hana.ondemand.com/#abap" target="_blank" rel="noopener noreferrer">ABAP Development Tools</a>
                                                            </li>
                                                            <li>
                                                                <a class="NavigationList__navigationLink--Icnc1 fontBookBP NavigationList__tier2--xVf7f" href="https://developers.sap.com/trials-downloads.html?search=Mobile+Development+Kit+Client" target="_self">Mobile Development Kit Client</a>
                                                            </li>
                                                            <li>
                                                                <a class="NavigationList__navigationLink--Icnc1 fontBookBP NavigationList__tier2--xVf7f" href="/tutorials/appstudio-onboarding.html" target="_self">SAP Business Application Studio</a>
                                                            </li>
                                                            <li>
                                                                <a class="NavigationList__navigationLink--Icnc1 fontBookBP NavigationList__tier2--xVf7f" href="/mission.dataintelligence-trial.html" target="_self">SAP Data Intelligence Trial</a>
                                                            </li>
                                                            <li>
                                                                <a class="NavigationList__navigationLink--Icnc1 fontBookBP NavigationList__tier2--xVf7f" href="https://developers.sap.com/tutorials/hana-trial-advanced-analytics.html" target="_self">SAP HANA Cloud Trial</a>
                                                            </li>
                                                            <li>
                                                                <a class="NavigationList__navigationLink--Icnc1 fontBookBP NavigationList__tier2--xVf7f" href="/trials-downloads.html" target="_self">All Trials &amp;Downloads</a>
                                                            </li>
                                                        </ul>
                                                    </div>
                                                </div>
                                            </div>
                                        </div>
                                        <div class="Grid__col-12--7Dsx8 Grid__col-sm-4--ay-1g Grid__col-lg-3--Afzxx ">
                                            <div class="NavigationColumn__root--jheSe NavigationColumn__tier2--QdzMQ">
                                                <h3 class="NavigationColumn__title--3x2kD">
                                                    <button disabled="" class="NavigationColumn__accordionOpener--5HFJI fontMediumBP NavigationColumn__tier2--QdzMQ" aria-disabled="true" aria-expanded="false">
                                                        <span>Site Information</span>
                                                    </button>
                                                </h3>
                                                <div>
                                                    <div>
                                                        <ul class="NavigationList__root--No5zo">
                                                            <li>
                                                                <a class="NavigationList__navigationLink--Icnc1 fontBookBP NavigationList__tier2--xVf7f" href="//www.sap.com/about/legal/privacy.html" target="_blank">Privacy</a>
                                                            </li>
                                                            <li>
                                                                <a class="NavigationList__navigationLink--Icnc1 fontBookBP NavigationList__tier2--xVf7f" href="https://www.sap.com/corporate/en/legal/terms-of-use.html" target="_blank" title=" ">Terms of Use</a>
                                                            </li>
                                                            <li>
                                                                <a class="NavigationList__navigationLink--Icnc1 fontBookBP NavigationList__tier2--xVf7f" href="//www.sap.com/about/legal/impressum.html" target="_blank">Legal Disclosure</a>
                                                            </li>
                                                            <li>
                                                                <a class="NavigationList__navigationLink--Icnc1 fontBookBP NavigationList__tier2--xVf7f" href="//www.sap.com/about/legal/copyright.html" target="_blank">Copyright</a>
                                                            </li>
                                                            <li>
                                                                <a class="NavigationList__navigationLink--Icnc1 fontBookBP NavigationList__tier2--xVf7f" href="//www.sap.com/about/legal/trademark.html" target="_blank">Trademark</a>
                                                            </li>
                                                            <li>
                                                                <a class="NavigationList__navigationLink--Icnc1 fontBookBP NavigationList__tier2--xVf7f" href="//www.sap.com/cmp/nl/sap-newsletter/index.html" target="_self">Newsletter</a>
                                                            </li>
                                                            <li>
                                                                <a class="NavigationList__navigationLink--Icnc1 fontBookBP NavigationList__tier2--xVf7f" href="http://www.sap.com/sitemap" target="_blank" title="Sitemap">Sitemap</a>
                                                            </li>
                                                            <li>
                                                                <a class="NavigationList__navigationLink--Icnc1 fontBookBP NavigationList__tier2--xVf7f" href="#" target="_self" title="Text View">Text View</a>
                                                            </li>
                                                        </ul>
                                                    </div>
                                                </div>
                                            </div>
                                        </div>
                                    </div>
                                    <div class="SubNavigation__root--FPOrQ SubNavigation__tier2--Bx55L">
                                        <div class="Grid__row--VKNKI ">
                                            <div class="Grid__col-12--7Dsx8 Grid__col-sm-8--SG-k- Grid__col-md-8--F+Bn+ Grid__col-lg-6--zgCt- SubNavigation__socialContainer--lVUk7">
                                                <div class="SocialLinks__root--tZ3T3 SocialLinks__tier2--SXpTV">
                                                    <h4 class="SocialLinks__title--nKCTL fontBookBP SocialLinks__tier2--SXpTV">Find us on</h4>
                                                    <ul class="SocialLinks__list--ftITi">
                                                        <li class="SocialLinks__item--0TUju">
                                                            <a class="SocialLinks__link--8zfws SocialLinks__tier2--SXpTV" href="https://www.facebook.com/sapdevelopers" title="Facebook" target="_blank" rel="noopener noreferrer" data-share-channel="facebook" data-share-tracking-analytics="FOLLOW" data-share-url="undefined?source=social-atw-facebook">
                                                                <div style="width:16px;height:16px"></div>
                                                            </a>
                                                        </li>
                                                        <li class="SocialLinks__item--0TUju">
                                                            <a class="SocialLinks__link--8zfws SocialLinks__tier2--SXpTV" href="https://twitter.com/sapdevs" title="twitter" target="_blank" rel="noopener noreferrer" data-share-channel="twitter" data-share-tracking-analytics="FOLLOW" data-share-url="undefined?source=social-atw-twitter">
                                                                <div style="width:16px;height:16px"></div>
                                                            </a>
                                                        </li>
                                                        <li class="SocialLinks__item--0TUju">
                                                            <a class="SocialLinks__link--8zfws SocialLinks__tier2--SXpTV" href="https://www.youtube.com/user/sapdevs" title="YouTube" target="_blank" rel="noopener noreferrer" data-share-channel="youtube" data-share-tracking-analytics="FOLLOW" data-share-url="undefined?source=social-atw-youtube">
                                                                <div style="width:16px;height:16px"></div>
                                                            </a>
                                                        </li>
                                                        <li class="SocialLinks__item--0TUju">
                                                            <a class="SocialLinks__link--8zfws SocialLinks__tier2--SXpTV" href="https://www.linkedin.com/company/sap-developers" title="LinkedIn" target="_blank" rel="noopener noreferrer" data-share-channel="linkedin" data-share-tracking-analytics="FOLLOW" data-share-url="undefined?source=social-atw-linkedin">
                                                                <div style="width:16px;height:16px"></div>
                                                            </a>
                                                        </li>
                                                        <li class="SocialLinks__item--0TUju">
                                                            <a class="SocialLinks__link--8zfws SocialLinks__tier2--SXpTV" href="https://github.com/sap" title="GitHub" target="_blank" rel="noopener noreferrer" data-share-channel="github" data-share-tracking-analytics="FOLLOW" data-share-url="undefined?source=social-atw-github">
                                                                <div style="width:16px;height:16px"></div>
                                                            </a>
                                                        </li>
                                                        <li class="SocialLinks__item--0TUju">
                                                            <a class="SocialLinks__link--8zfws SocialLinks__tier2--SXpTV" href="mailto:developers@sap.com?body=Dear%20SAP%20Devs,&amp;subject=Feedback:%20(update%20subject%20here)" title="Email share" target="_self" data-share-channel="email" data-share-tracking-analytics="FOLLOW" data-share-url="undefined?source=social-atw-email">
                                                                <div style="width:16px;height:16px"></div>
                                                            </a>
                                                        </li>
                                                    </ul>
                                                </div>
                                            </div>
                                            <div class="Grid__col-12--7Dsx8 Grid__col-sm-4--ay-1g Grid__col-md-4--i2Poc Grid__col-lg-6--zgCt- ">
                                                <div class="SubNavigation__logoContainer--yWJsV">
                                                    <div class="Logo__root--RRyCk">
                                                        <a class="Logo__logo--XLOCI" href="/" target="_self" title="SAP">
                                                            <img src="/dam/application/shared/logos/sap-logo-svg.svg/sap-logo-svg.svg" alt="SAP" class="Logo__image--KgNwb"/>
                                                        </a>
                                                    </div>
                                                </div>
                                            </div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </footer>
            <b class="accessibility">
                <a href="#page">Back to top</a>
            </b>
        </div>
        <script>
            try {
                if (!!window._satellite) {
                    _satellite.pageBottom();
                }
            } catch (e) {
                console.error("Error while calling _satellite.pageBottom(), Error thrown : " + e);
            }
        </script>
        <script src="/etc.clientlibs/sapdx/clientlibs/clientlib-lightbox-util.min.11fc804d25862b7db2745949b35ddb2b.js"></script>
        <script src="/etc.clientlibs/sapdx/clientlibs/clientlib-lightbox-lazy-init.min.3380c447500e657527dbc2c430bf9ba3.js"></script>
        <span class='lazy-loader-event-wrapper' data-categories='apps.sapdx.lightbox'>
            <span class='lazy-css' data-src="/etc.clientlibs/sapdx/clientlibs/clientlib-lightbox.min.18daxb2.1.0.4454.css"></span>
            <span class='lazy-script' data-src="/etc.clientlibs/sapdx/clientlibs/clientlib-lightbox.min.18daxb2.1.0.4454.js"></span>
        </span>
    </body>
</html>
