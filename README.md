
  










<!DOCTYPE html>
    <!--[if lt IE 7 ]>
        <html class="ie6" ng-app="PartSimApp">
    <![endif]-->
    <!--[if IE 7 ]>
        <html class="ie7" lang="en" ng-app="PartSimApp">
    <![endif]-->
    <!--[if IE 8 ]>
        <html class="ie8" lang="en" ng-app="PartSimApp">

    <![endif]-->
    <!--[if IE 9 ]>
        <html class="ie9" lang="en" ng-app="PartSimApp">
    <![endif]-->
    <!--[if IE 10 ]>
        <html class="ie10" lang="en" ng-app="PartSimApp">
    <![endif]-->
    <!--[if IE 11 ]>
        <html class="ie11" lang="en" ng-app="PartSimApp">
    <![endif]-->
    <!--[if !(IE)]><!-->
        <html lang="en" ng-app="PartSimApp">
    <!--<![endif]-->
    <head>
        <!--[if IE 8 ]>
            <script>
                document.createElement('sidebar-accordion');
                document.createElement('sidebar-section');
                document.createElement('sidebar-component');
                document.createElement('sidebar-category');
                document.createElement('sidebar-subcategory');
            </script>

            <script src="//cdn2.partsim.com/static/js/library/es5-shim.min.js"></script>
            <script src="//cdn2.partsim.com/static/js/library/es5-sham.min.js"></script>
        <![endif]-->
        <!--[if IE 9 ]>
            <script src="//cdn2.partsim.com/static/js/library/es5-shim.min.js"></script>
            <script src="//cdn2.partsim.com/static/js/library/es5-sham.min.js"></script>
        <![endif]-->

        <meta charset="utf-8" http-equiv="X-UA-Compatible" content="IE=Edge,chrome=IE6">
        <meta name="WT.z_webapp" content="PartSim">
        <meta name="WT.cg_n" content="PartSim">
        <meta name="WT.cg_s" content="Simulator">
        <meta name="description" content="PartSim is a free and easy to use circuit simulator that includes a full SPICE simulation engine, web-based schematic capture tool, a graphical waveform viewer that runs in your web browser.">
        <meta name="keywords" content="online circuit simulator, spice simulator, spice circuit simulator, circuit simulation, circuit sim, free online circuit simulator, browser circuit simulator, free circuit simulator software, circuit simulation program, circuit design simulator">

        <title>Online Circuit Simulator with SPICE</title>

        <link rel="icon" href="/static/img/favicon.ico" />
        <link rel="stylesheet" href="/static/CACHE/css/4f5f699890b5.css" type="text/css" media="screen" />
        <link rel="stylesheet" href="/static/css/smoothness/jquery-ui-1.10.3.custom.min.css" type="text/css" media="screen" />


        <!-- properties sidebar -->
        <link rel="stylesheet" href="/static/css/property_sidebar_styles-1.0.7.min.css" type="text/css" media="screen" />
        
            <!--Searchable Sidebar-->
            <link rel="stylesheet" href="//cdn2.partsim.com/static/js/library/searchable-sidebar-partsim-1.3.3/css/searchable-sidebar-partsim.min.css" type="text/css" media="screen" />
        
        <link rel="stylesheet"
              href="/static/css/jPicker-1.1.6.min.css"
              type="text/css"
              media="screen" />
        <link rel="stylesheet" href="/static/CACHE/css/72cc40176487.css" type="text/css" media="screen" />

        <!-- Google Tag Manager -->
        <script>(function(w,d,s,l,i){w[l]=w[l]||[];w[l].push({'gtm.start':
            new Date().getTime(),event:'gtm.js'});var f=d.getElementsByTagName(s)[0],
            j=d.createElement(s),dl=l!='dataLayer'?'&l='+l:'';j.async=true;j.src=
            'https://www.googletagmanager.com/gtm.js?id='+i+dl;f.parentNode.insertBefore(j,f);
            })(window,document,'script','dataLayer','GTM-NMNZ3NH');</script>
        <!-- End Google Tag Manager -->

        <script type="text/javascript">if(!window.console){window.console={};window.console.log=function(){};}
var baseImagePath="";var baseImagePath="../";mxLoadStylesheets=false;mxLoadResources=false;EEBasepath="/static/";AngularWhitelist=["//cdn2.partsim.com/**"];TemplatePath="//cdn2.partsim.com/production/0.33.1/deploy/static/";ComponentAPIBasepath="//components.schematics.com/partsim/";APIBasepath=location.protocol+'//'+location.host+'/';DialogPath="/dialog/";EventLoggerPath="aspen_event_logger/";ModuleBasepath="//cdn2.partsim.com/production/0.33.1/deploy/static/";mxBasePath="/static/";mxImageBasePath="/static/";componentApi={lang:"en",path:"//components.schematics.com/arrow/",proxyPath:"//components.schematics.com/arrow/",universalSearch:"//components.schematics.com/arrow/",proxyUniversalSearch:"//components.schematics.com/arrow/",symboldataURL:"//component-server-site-media.s3.amazonaws.com/",partsimSearchURL:"//components.schematics.com/partsim_search/",schematicsSymbols:""};sidebarOptions={symbolsFlag:false,allowCategoryLevelPartsAndFilters:false,loadFilters:true,filterListType:'category',bomImport:false,designStarters:false,customSymbols:false,partInfoSymbols:false};</script>

        
            
<script type="text/javascript">(function(i,s,o,g,r,a,m){i['GoogleAnalyticsObject']=r;i[r]=i[r]||function(){(i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o),m=s.getElementsByTagName(o)[0];a.async=1;a.src=g;m.parentNode.insertBefore(a,m)})(window,document,'script','//www.google-analytics.com/analytics.js','ga');ga('create','UA-35107113-2','auto');ga('send','pageview');</script>

        

        <!-- This needs to be loaded on this part it will not work if loaded after the body loads. -->
        <script src="//cdn2.partsim.com/static/js/library/react_0.14.8/react.min.js"></script>
        <script src="//cdn2.partsim.com/static/js/library/react_0.14.8/react-dom.min.js"></script>
    </head>
    <body ng-controller="AppController">

        <!-- Google Tag Manager (noscript) -->
        <noscript><iframe src="https://www.googletagmanager.com/ns.html?id=GTM-NMNZ3NH"
            height="0" width="0" style="display:none;visibility:hidden"></iframe>
        </noscript>
        <!-- End Google Tag Manager (noscript) -->
    

        <div id="jPicker"></div>

        <div id="top_bar">
            <div id="projectname_bar" class="noclick_div">
                <div class="projectbar_button">
                    <span id="project_name">
                        Project Name
                    </span>
                    <span id="unsaved_indicator">
                        (unsaved)
                    </span>
                    <span class="hidden" id="saving_indicator">
                        (saving
                        <img src="/static/img/loading.gif" />)
                    </span>
                    <span class="hidden" id="loading_indicator">
                        (loading project
                        <img src="/static/img/loading.gif" />)
                    </span>
                </div>
            </div>

            <div id="projectBar" class="shadow">
                <div id="logo_header"
                     title="Click to return to the projects page" >
                    <img src="/static/img/toolbar_logo.png"
                         width="100"
                         height="16"
                         alt="Partsim" />
                </div>

                <div class="projectbar_button" id="help_options_button">
                    <div id="help_options">
                        Help
                        <span class="contact_us_arrow"></span>
                    </div>
                </div>

                <div class="projectbar_button" id="projects_button">
                    Projects
                </div>

                <div class="projectbar_button" id="login_button">
                    <span id="login">Login</span>
                </div>

                <div class="projectbar_button" id="signup_button">
                    <span id="#sign_up">Sign-Up</span>
                </div>

                <div class="projectbar_button" id="user_button">
                    <span>Username</span>
                    <span id="logout">Logout</span>
                </div>
            </div>

            <div id="help_dropdown" style="display: none;">
                <ul>
		<!-- <li>
                        <a href="http://help.partsim.com/support/discussions"
                           target="_blank" id="help_forums_button">Forum</a>
                    </li> -->                    
                    <li>
                        <a href="#" id="keyboard_shortcuts_button">Keyboard Shortcuts</a>
                    </li>
                    <li>
                        <a href="/examples" target="_blank" id="examples_button">Examples</a>
                    </li>
                </ul>
            </div>

            <div id="tabs">
                <p>Site Navigation</p>
                <ul>
                    <li id="tab_main" class="tab_main tab_first tab_hot">
                        Subcircuit
                    </li>
                    <li id="tab_text" class="tab_text" style="display:none;">
                        Text Align
                    </li>
                    <li id="tab_report" class="tab_report" style="display:none;">
                        Report
                        <span class="ui-icon ui-icon-close"></span>
                    </li>
                    <li id="tab_chart_1" class="tab_charts" style="display:none;">
                        Chart
                        <span class="ui-icon ui-icon-close"></span>
                    </li>
                    <li id="tab_chart_2" class="tab_charts" style="display:none;">
                        Chart
                        <span class="ui-icon ui-icon-close"></span>
                    </li>
                    <li id="tab_chart_3" class="tab_charts" style="display:none;">
                        Chart
                        <span class="ui-icon ui-icon-close"></span>
                    </li>
                    <li id="tab_bom" class="tab_bom">
                        BOM
                    </li>
                </ul>
            </div>

            <div id="toolbar_bg">
                <div id="toolbar">
                    <ul id="menu_main" class="menu_group">
                        <li class="menu_wrap">
                            <div class="menu_wrap_label">
                                Project
                            </div>
                            <ul class="menu_sub_group">
                                <li id="toolbar_save" >
                                    <div class="img"></div>
                                    <div class="menu_text">
                                        Save
                                    </div>
                                </li>
                                <li id="toolbar_saveas">
                                    <div class="img"></div>
                                    <div class="menu_text">
                                        Save As
                                    </div>
                                </li>
                                <li id="toolbar_new">
                                    <div class="img"></div>
                                    <div class="menu_text">
                                        New
                                    </div>
                                </li>
                                <li id="toolbar_open">
                                    <div class="img"></div>
                                    <div class="menu_text">
                                        Open
                                    </div>
                                </li>
                            </ul>
                        </li>
                        <li class="menu_wrap">
                            <div class="menu_wrap_label">
                                Spice
                            </div>
                            <ul class="menu_sub_group">
                                <li id="toolbar_run" >
                                    <div class="img"></div>
                                    <div class="menu_text">
                                        Run
                                    </div>
                                </li>
                                <li id="toolbar_model_manager"
                                    class="model-manager-button">
                                    <div class="img"></div>
                                    <div class="menu_text">
                                        Models
                                    </div>
                                </li>
                                <!--
                                <li id="toolbar_showdc">
                                    <div class="img"></div>
                                    <div class="menu_text">Show DC</div>
                                </li>
                                -->
                            </ul>
                        </li>
                        <li class="menu_wrap">
                            <div class="menu_wrap_label">
                                Output
                            </div>
                            <ul class="menu_sub_group">
                                <li id="toolbar_export">
                                    <div class="img"></div>
                                    <div class="menu_text">
                                        Export
                                    </div>
                                </li>
                                <li id="toolbar_netlist">
                                    <div class="img"></div>
                                    <div class="menu_text">
                                        Netlist
                                    </div>
                                </li>
                                <!--
                                <li id="toolbar_show">
                                    <div class="img"></div>
                                    <div class="menu_text">Show Netlist</div>
                                </li>
                                -->
                                <li id="toolbar_share">
                                    <div class="img"></div>
                                    <div class="menu_text">
                                        Share
                                    </div>
                                </li>
                                <li id="toolbar_print">
                                    <div class="img"></div>
                                    <div class="menu_text">
                                        Print
                                    </div>
                                </li>
                            </ul>
                        </li>
                        <li class="menu_wrap">
                            <div class="menu_wrap_label">
                                Edit
                            </div>
                            <ul class="menu_sub_group">
                                <li id="toolbar_cut" >
                                    <div class="img"></div>
                                    <div class="menu_text">
                                        Cut
                                    </div>
                                </li>
                                <li id="toolbar_copy">
                                    <div class="img"></div>
                                    <div class="menu_text">
                                        Copy
                                    </div>
                                </li>
                                <li id="toolbar_paste">
                                    <div class="img"></div>
                                    <div class="menu_text">
                                        Paste
                                    </div>
                                </li>
                                <li id="toolbar_delete">
                                    <div class="img"></div>
                                    <div class="menu_text">
                                        Delete
                                    </div>
                                </li>
                            </ul>
                        </li>
                        <li class="menu_wrap">
                            <div class="menu_wrap_label">
                                History
                            </div>
                            <ul class="menu_sub_group">
                                <li id="toolbar_undo" >
                                    <div class="img"></div>
                                    <div class="menu_text">
                                        Undo
                                    </div>
                                </li>
                                <li id="toolbar_redo">
                                    <div class="img"></div>
                                    <div class="menu_text">
                                        Redo
                                    </div>
                                </li>
                            </ul>
                        </li>
                        <li class="menu_wrap">
                            <div class="menu_wrap_label" >
                                Insert
                            </div>
                            <ul class="menu_sub_group">
                                <li id="toolbar_textbox" >
                                    <div class="img"></div>
                                    <div class="menu_text" >
                                        Textbox
                                    </div>
                                </li>
                            </ul>
                        </li>
                    </ul>

                    <ul id="menu_object" class="menu_group">
                        <li class="menu_wrap">
                            <div class="menu_wrap_label">
                                Group
                            </div>
                            <ul class="menu_sub_group">
                                <li id="toolbar_group">
                                    <div class="img"></div>
                                    <div class="menu_text">
                                        Group
                                    </div>
                                </li>
                                <li id="toolbar_ungroup">
                                    <div class="img"></div>
                                    <div class="menu_text">
                                        UnGroup
                                    </div>
                                </li>
                            </ul>
                        </li>
                        <li class="menu_wrap">
                            <div class="menu_wrap_label">
                                Level
                            </div>
                            <ul class="menu_sub_group">
                                <li id="toolbar_raise">
                                    <div class="img"></div>
                                    <div class="menu_text">
                                        Raise
                                    </div>
                                </li>
                                <li id="toolbar_lower">
                                    <div class="img"></div>
                                    <div class="menu_text">
                                        Lower
                                    </div>
                                </li>
                            </ul>
                        </li>
                        <li class="menu_wrap">
                            <div class="menu_wrap_label">
                                Transform
                            </div>
                            <ul class="menu_sub_group">
                                <li id="toolbar_flip_v">
                                    <div class="img"></div>
                                    <div class="menu_text">
                                        Flip V
                                    </div>
                                </li>
                                <li id="toolbar_flip_h">
                                    <div class="img"></div>
                                    <div class="menu_text">
                                        Flip H
                                    </div>
                                </li>
                                <li id="toolbar_rotate">
                                    <div class="img"></div>
                                    <div class="menu_text">
                                        Rotate
                                    </div>
                                </li>
                            </ul>
                        </li>
                        <li class="menu_wrap">
                            <div class="menu_wrap_label">
                                Align
                            </div>
                            <ul class="menu_sub_group">
                                <li id="toolbar_align_left">
                                    <div class="img"></div>
                                    <div class="menu_text">
                                        Left
                                    </div>
                                </li>
                                <li id="toolbar_align_center">
                                    <div class="img"></div>
                                    <div class="menu_text">
                                        Center
                                    </div>
                                </li>
                                <li id="toolbar_align_right">
                                    <div class="img"></div>
                                    <div class="menu_text">
                                        Right
                                    </div>
                                </li>
                                <li id="toolbar_align_top">
                                    <div class="img"></div>
                                    <div class="menu_text">
                                        Top
                                    </div>
                                </li>
                                <li id="toolbar_align_middle">
                                    <div class="img"></div>
                                    <div class="menu_text">
                                        Middle
                                    </div>
                                </li>
                                <li id="toolbar_align_bottom">
                                    <div class="img"></div>
                                    <div class="menu_text">
                                        Bottom
                                    </div>
                                </li>
                            </ul>
                        </li>
                        <li class="menu_wrap">
                            <div class="menu_wrap_label">
                                Background
                            </div>
                            <ul class="menu_sub_group">
                                <li id="toolbar_fill">
                                    <div class="img"></div>
                                    <div class="menu_text">
                                        Fill
                                    </div>
                                </li>
                                <li id="toolbar_gradient">
                                    <div class="img"></div>
                                    <div class="menu_text">
                                        Gradient
                                    </div>
                                </li>
                            </ul>
                        </li>
                    </ul>

                    <ul id="menu_text" class="menu_group">
                        <li class="menu_wrap">
                            <div class="menu_wrap_label">
                                Size &amp; Color
                            </div>
                            <ul class="menu_sub_group">
                                <li id="toolbar_bigger">
                                    <div class="img"></div>
                                    <div class="menu_text">
                                        Bigger
                                    </div>
                                </li>
                                <li id="toolbar_smaller">
                                    <div class="img"></div>
                                    <div class="menu_text">
                                        Smaller
                                    </div>
                                </li>
                                <li id="toolbar_color">
                                    <div class="img"></div>
                                    <div class="menu_text">
                                        Color
                                    </div>
                                </li>
                            </ul>
                        </li>
                        <li class="menu_wrap">
                            <div class="menu_wrap_label">
                                Style
                            </div>
                            <ul class="menu_sub_group">
                                <li id="toolbar_bold">
                                    <div class="img"></div>
                                    <div class="menu_text">
                                        Bold
                                    </div>
                                </li>
                                <li id="toolbar_italic">
                                    <div class="img"></div>
                                    <div class="menu_text">
                                        Italic
                                    </div>
                                </li>
                                <li id="toolbar_underline">
                                    <div class="img"></div>
                                    <div class="menu_text">
                                        ULine
                                    </div>
                                </li>
                            </ul>
                        </li>
                        <li class="menu_wrap">
                            <div class="menu_wrap_label">
                                Horizontal Align
                            </div>
                            <ul class="menu_sub_group">
                                <li id="toolbar_text_left">
                                    <div class="img"></div>
                                    <div class="menu_text">
                                        Left
                                    </div>
                                </li>
                                <li id="toolbar_text_center">
                                    <div class="img"></div>
                                    <div class="menu_text">
                                        Center
                                    </div>
                                </li>
                                <li id="toolbar_text_right">
                                    <div class="img"></div>
                                    <div class="menu_text">
                                        Right
                                    </div>
                                </li>
                            </ul>
                        </li>
                        <li class="menu_wrap">
                            <div class="menu_wrap_label">
                                Vertical Align
                            </div>
                            <ul class="menu_sub_group">
                                <li id="toolbar_text_top">
                                    <div class="img"></div>
                                    <div class="menu_text">
                                        Top
                                    </div>
                                </li>
                                <li id="toolbar_text_middle">
                                    <div class="img"></div>
                                    <div class="menu_text">
                                        Middle
                                    </div>
                                </li>
                                <li id="toolbar_text_bottom">
                                    <div class="img"></div>
                                    <div class="menu_text">
                                        Bottom
                                    </div>
                                </li>
                            </ul>
                        </li>
                    </ul>

                    <ul id="menu_bom" class="menu_group">
                        <li class="menu_wrap">
                            <div class="menu_wrap_label">
                                Output
                            </div>
                            <ul class="menu_sub_group">
                                <li id="toolbar_bom_export">
                                    <div class="img"></div><div class="menu_text">
                                        Export
                                    </div>
                                </li>
                                
                                <li id="toolbar_bom_order">
                                    <div class="img"></div>
                                    <div class="menu_text">
                                        Order Parts
                                    </div>
                                </li>
                            </ul>
                        </li>
                    </ul>
                </div>
            </div>
        </div>

        <div id="tool_body">
            <div id="sidebar" >
                <div id="sidebar_stuff">
                    <div id="sidebar_tabs">
                        <ul>
                            <li class='tab_hot tab_first' content='#sidebar_components'>
                                <span>
                                    Components
                                </span>
                            </li>
                            <li content='#sidebar_probes'>
                                <span>
                                    Probes
                                </span>
                            </li>
                        </ul>
                    </div>
                    <div id="sidebar_content">
                        <div id="sidebar_probes" class="sidebar sidebar_shadow">
                            

<div>
    <!-- This could be a neat idea...
    <div id="probe_sets">
        <div class="title">Probe Set</div>
        <div>
            <select name="probe_sets">
                <option value="All">All</option>
                <option value="DC">DC Simulation</option>
                <option value="AC">AC Simulation</option>
                <option value="Tran">Transient Simulation</option>
            </select>
        </div>
    </div>
    -->
    <div id="probe_nets">
        <div class="title">Nets &amp; Currents</div>
        <div class="probe_nets">
            <select name="nets">
                <!-- populated by javascript.
                <option value="V1">V1</option>
                -->
            </select>
            <button class="probe_add">Add Probe</button>
        </div>
    </div>

    <!-- Example of input sections.
    <span>A Longer Label</span>
    <input type="text" name="1"/>
    <input type="checkbox" name="1"/>
    <span>Pretty darn long!!</span>
    <input type="text" name="1"/>
    <input type="checkbox" name="1"/>

    -->
    <div id="sim_probes">
        <div class="title">Probes</div>
        <!-- Probe Point example
        <div class='probeitem'>
            <span>probe name, as an expression</span>
            <button>Edit</button>
            <button>Delete</button>
        </div>

        -->
        <div id="probe_list">
            <div class='probeitem'>
                <span>Vin</span>
                <div>
                    <button class="probeeditcancel"></button>
                    <button class="probeedit"></button>
                    <button class="probedel"></button>
                </div>
            </div>
            <div class='probeitem'>
                <span><input type="text" value="blah"/></span>
                <div>
                    <button class="probeeditcancel"></button>
                    <button class="probeedit"></button>
                    <button class="probedel"></button>
                </div>
            </div>
        </div>
        <!-- EXPRESSSIONS - remove for now.
        <div class="add_expr">
            <button>Add Probe Expression</button>
        </div>
        -->
    </div>
    <!--
    <div id='probe_options'>
        <div class="title">Options</div>
        <div>
            <input type='radio' name='probe_radio' value='a' id='pr1'>
            <label for=pr1>Type 1</label>
            </input>
            <input type='radio' name='probe_radio' value='b' id='pr2'>
            <label for=pr2>Type 2</label>
            </input>
        </div>
    </div>
    -->
</div>

                        </div>
                        <div id="sidebar_options" class="sidebar sidebar_shadow">
                            <div class="clearfix">
                                <div class="title">
                                    Options
                                </div>
                                <span>Option one</span>
                                <input type="text" name="opt1"/>
                                <input type="checkbox" name="1"/>
                                <span>Option two</span>
                                <input type="text" name="opt2"/>
                                <input type="checkbox" name="1"/>
                            </div>
                        </div>
                        <div id="sidebar_container" class="component_mode" ng-controller="SideBarMainController">
                            <div id="vendor_schematic_logo">
                                <div id="vendor_sidebar_link"></div>
                            </div>
                            <div server-status refresh="loadSearchItems"></div>
                            <div id="searchbar" searchbar
                                 ng-class="{'searchbar-closed':!searchBarOpened,'searchbar-opened':searchBarOpened}">
                            </div>
                        </div>
                    </div>
                </div>
            </div>

            <div class="vendor_floating_logo_container">
                <a class="vendor_home_link" href="https://www.arrow.com/" target="_blank">
                    <div class="vendor_floating_logo"></div>
                </a>
            </div>

            <div id="schematic-wrapper" class="vendorBarOn">
                <div id="schematic-viewport" class="schzoom">
                    <div id="schematic" class="schzoom"></div>
                    
                    <div class="schzoom zoom-grid grid-10"></div>
                    
                    <div class="schzoom zoom-grid grid-20"></div>
                    
                    <div class="schzoom zoom-grid grid-30"></div>
                    
                    <div class="schzoom zoom-grid grid-40"></div>
                    
                    <div class="schzoom zoom-grid grid-50"></div>
                    
                    <div class="schzoom zoom-grid grid-60"></div>
                    
                    <div class="schzoom zoom-grid grid-70"></div>
                    
                    <div class="schzoom zoom-grid grid-80"></div>
                    
                    <div class="schzoom zoom-grid grid-90"></div>
                    
                    
                    <div class="schzoom zoom-grid grid-100"></div>
                    
                    <div class="schzoom zoom-grid grid-120"></div>
                    
                    <div class="schzoom zoom-grid grid-140"></div>
                    
                    <div class="schzoom zoom-grid grid-160"></div>
                    
                    <div class="schzoom zoom-grid grid-180"></div>
                    
                    <div class="schzoom zoom-grid grid-200"></div>
                    
                    <div class="schzoom zoom-grid grid-220"></div>
                    
                    <div class="schzoom zoom-grid grid-240"></div>
                    
                    <div class="schzoom zoom-grid grid-260"></div>
                    
                    <div class="schzoom zoom-grid grid-280"></div>
                    
                    <div class="schzoom zoom-grid grid-300"></div>
                    
                    <div class="schzoom zoom-grid grid-320"></div>
                    
                    <div class="schzoom zoom-grid grid-340"></div>
                    
                    <div class="schzoom zoom-grid grid-360"></div>
                    
                    <div class="schzoom zoom-grid grid-380"></div>
                    
                    <div class="schzoom zoom-grid grid-400"></div>
                    
                </div>
            </div>


            <div id="zoom_bar" class="tool_mode">
                <div id="left_sidebar_toggle" unselectable="on"><div class="left_direction">&nbsp;</div></div>
                <div id="z_in" unselectable="on">&nbsp;</div>
                <div id="z_out" unselectable="on">&nbsp;</div>
                <div id="z_fit" unselectable="on">&nbsp;</div>
            </div>

            <div id="right_sidebar_toggle" unselectable="on">
                <div class="right_direction">&nbsp;</div>
            </div>

            <div id="properties_sidebar"></div>

            <div id="release_footer">
            <span class="copyright">آ©</span>
            <span class="copyright_year">2020</span>
            <span class="release_version">Release 2.2.7</span>
            <div class="new_notification hidden">New</div>
        </div>
        </div>

        <div id="release_notes_dialog" title="Release Notes"><div class="release_block latest">
    <div class="release_number">What's <span class="red">New</span> in Release 2.2.7</div>
    <div class="release_date">May 23, 2018</div>
    <div class="release_content">
        <ul>
            <li>Added release notes feature.</li>
        </ul>
    </div>
</div>

<div class="release_block">
    <div class="release_number">Release 2.2.6</div>
    <div class="release_date">April 11, 2018</div>
    <div class="release_content">
        <ul>
            <li>Changed project number for example Full-wave Rectifier with a Smoothing Capacitor.</li>
            <li>Added center schematic option on right click menu.</li>
            <li>Updated BOM upload automation using Arrow's BOM API.</li>
            <li>Update properties sidebar bundle.</li>
        </ul>
    </div>
</div>

<div class="release_block">
    <div class="release_number">2.2.5</div>
    <div class="release_date">November 28, 2017</div>
    <div class="release_content">
        <ul>
            <li>Fixed bug where user can't open projects if user's first/last name has unicode characters</li>
        </ul>
    </div>
</div>

<div class="release_block">
    <div class="release_number">Release 2.2.4</div>
    <div class="release_date">November 23, 2017</div>
    <div class="release_content">
        <ul>
            <li>Added project revision feature.</li>
            <li>Fixed empty exported graphs</li>
        </ul>
    </div>
</div>

<div class="release_block">
    <div class="release_number">Release 2.2.1</div>
    <div class="release_date">September 19, 2017</div>
    <div class="release_content">
        <ul>
            <li>Fixed internal server error for logout API</li>
            <li>Fixed changing paper size to ansi issue</li>
        </ul>
    </div>
</div>

<div class="release_block">
    <div class="release_number">Release 2.2</div>
    <div class="release_date">August 30, 2017</div>
    <div class="release_content">
        <ul>
            <li>Added saving and loading indicators.</li>
        </ul>
    </div>
</div>

<div class="release_block">
    <div class="release_number">Release 2.1</div>
    <div class="release_date">July 19, 2017</div>
    <div class="release_content">
        <ul>
            <li>Update export option value for ansi b page format.</li>
            <li>Added keyboard shortcuts dialog.</li>
            <li>Added more simulation examples.</li>
            <li>Update properties sidebar with the grid type option.</li>
            <li>Update properties sidebar for page format and viewport options.</li>
        </ul>
    </div>
</div>
<div class="release_block">
    <div class="release_number">Release 2.0.6</div>
    <div class="release_date">August 09, 2017</div>
    <div class="release_content">
        <ul>
            <li>Updated screenshot for Full-wave Rectifier with Smoothing Capacitor.</li>
        </ul>
    </div>
</div>
<div class="release_block">
    <div class="release_number">Release 2.0.5</div>
    <div class="release_date">August 6, 2017</div>
    <div class="release_content">
        <ul>
            <li>Added new example diagrams.</li>
        </ul>
    </div>
</div>
<div class="release_block">
    <div class="release_number">Release 2.0.4</div>
    <div class="release_date">April 26, 2017</div>
    <div class="release_content">
        <ul>
            <li>Update styling of zoom buttons on embed.</li>
            <li>Fixed missing page tab.</li>
        </ul>
    </div>
</div>

<div class="release_block">
    <div class="release_number">Release 2.0</div>
    <div class="release_date">March 31, 2017</div>
    <div class="release_content">
        <ul>
            <li>Added new searchable sidebar feature.</li>
        </ul>
    </div>
</div>
</div>

        <div id="pagetab_anchor" class="tool_mode">
            <div id="pagetab_div">
                <ul id="pages">
                </ul>
                <ul id="add_page">
                </ul>
            </div>
        </div>

        <div id="status_window" style="display:none;">
            <div id="simstatus">
                <div>
                    <span>
                        Simulation Status:
                    </span>
                    <span id="statusval">
                        Idle
                    </span>
                </div>
                <div id="statusdesc"></div>
            </div>
            <div id="simstatus_btn">
                <button type="button" class="ui-button ui-widget ui-state-default ui-corner-all ui-button-text-only">Close</button>
                <button type="button" class="ui-button ui-widget ui-state-default ui-corner-all ui-button-text-only" disabled="true" style="display:none;">Cancel Sim</button>
            </div>
        </div>

        <div id="bom_page" class="bom_mode">
            <table id="bom_table" class="display"></table>
        </div>

        <div id="report_page" class="report_mode">
            <div id="sim_report" class="sim_report">
                <div id="dc_operatingpoint">
                </div>
                <textarea>
                    Spice Simulation Output
                </textarea>
            </div>
            <div id="circuit_file" class="sim_report">
                <textarea>
                    Circuit File
                </textarea>
            </div>
        </div>

        <div id="sim_charts">
            <div id="chart_page_1" class="chart_page curr_chart">
                <div id="sim_buttons_1" class="sim_buttons">
                    <button >Cursor 1</button>
                    <button >Cursor 2</button>
                </div>
                <div id="sim_plot_1" class="sim_plot">
                </div>
            </div>
            <div id="chart_page_2" class="chart_page">
                <div id="sim_buttons_2" class="sim_buttons">
                    <button >Cursor 1</button>
                    <button >Cursor 2</button>
                </div>
                <div id="sim_plot_2" class="sim_plot">
                </div>
            </div>
            <div id="chart_page_3" class="chart_page">
                <div id="sim_buttons_3" class="sim_buttons">
                    <button >Cursor 1</button>
                    <button >Cursor 2</button>
                </div>
                <div id="sim_plot_3" class="sim_plot">
                </div>
            </div>
        </div>

        <div id="splash">
            <h1>PartSim Circuit Simulator</h1>
            <p>The app is loading, please wait.</p>
            <p class="status">loading component data...</p>
        </div>

        <div id="help">
            <ul id="help_nav">
                <li><a href="/help/introduction.html" class="first hot">Introduction</a></li>
                <li><a href="/help/save_project.html">Save/Open Projects</a></li>
                <li><a href="/help/placing_symbols.html">Placing Symbols</a></li>
                <li><a href="/help/custom_symbols.html">Custom Symbols</a></li>
                <li><a href="/help/wiring_symbols.html">Wiring Symbols</a></li>
                <li><a href="/help/text_editing.html">Text Editing</a></li>
                <li><a href="/help/share_and_export.html">Share and Export</a></li>
                <li><a href="/help/bom_manager.html">BOM Manager</a></li>
            </ul>
            <div id="help_content_wrap">
                <div id="help_content"></div>
            </div>
        </div>

        <div id="netlist_dialog">
            <textarea class="ui-corner-all ui-widget-content">
                Circuit File
            </textarea>
        </div>

        <div id="merge-net-confirm" title="Merge schematic nets?" style="display:none;">
            <p>
                Merge net A into net B?
            </p>
        </div>

        <div id="properties"></div>

        <div id="export_dialog" style="display:none;">
            <input type='radio' name='format' value='png' class="image_export" checked="checked" />Image (PNG)<br/>
            <input type='radio' name='format' value='svg' class="image_export" />Image (SVG)<br/>
            <input type='radio' name='format' value='pdf' class="pdf_export" />Document (PDF)<br/>

            <div id="export_dialog_options" class="export_options">
                <div class="option_title" id="image_export_title"><label class="title">Image Options</label></div>
                <div class="option_title" id="pdf_export_title"><label class="title">PDF Options</label></div>
                <div class="options" id="pages_to_export">
                    <label for="export_pages" >Pages:</label>
                    <input type='radio' name='export_pages' value='current' checked="checked"/>Current Page
                    <input type='radio' name='export_pages' value='all' />All Pages
                    <hr>
                </div>
                <div class="options" id="selection_to_export">
                    <label for="export_style" >Export Area:</label>
                    <select id="export_style" name="shrink">
                        <option value="shrink" selected>Active Area</option>
                        <option value="full" >Full Page</option>
                    </select>
                    <hr>
                </div>
                <div class="options" id="orientation_to_export">
                    <label for="export_page_orientation" >Orientation:</label>
                    <input type='radio' name='export_page_orientation' value='portrait' checked='checked' />Portrait
                    <input type='radio' name='export_page_orientation' value='landscape' />Landscape
                    <hr>
                </div>
                <div class="options" id="papersize_to_export">
                    <label for="export_paper_size" >Paper Size:</label>
                    <select id="export_paper_size" name="paper_size">
                        <option value="freesize" selected>No Size</option>
                        <option value="letter">Letter (8.5in x 11in)</option>
                        <option value="legal">Legal (8.5in x 14in)</option>
                        <option value="a3">A3 (11.7in x 16.5in)</option>
                        <option value="a4">A4 (8.27in x 11.7in)</option>
                        <option value="b3">B3 (13.9in x 19.7in)</option>
                        <option value="b4">B4 (9.84in x 13.9in)</option>
                        <option value="ansib">ANSI B (11in x 17in)</option>
                    </select>
                    <hr>
                </div>
            </div>
        </div>

        <div name="model-manager" class="model-manager"></div>
        <div id="spice_run_dialog" style="display:none;"></div>
        <div id="super_src_dialog" style="display:none;"></div>
        <div id="controlled_src_dialog" style="display:none;"></div>
        <div id="component_dialog" style="display:none;"></div>
        <div id="dk_search_dialog" style="display:none;">
            <iframe id="dk_search_iframe" width="100%" height="100%"></iframe>
        </div>

        

        <script src="//cdn2.partsim.com/static/js/library/jquery-1.10.2.min.js"></script>
        <script src="//cdn2.partsim.com/static/js/library/jquery-migrate-1.2.1.min.js"></script>
        <script src="//cdn2.partsim.com/static/js/library/jquery.xdomainrequest.min.js"></script>
        <script src="//cdn2.partsim.com/static/js/library/jquery-ui-1.10.3.custom.min.js"></script>
        <script src="//cdn2.partsim.com/static/js/library/jquery.ui.touch-punch.min.js"></script>
        <script src="//cdn2.partsim.com/static/js/library/amplify.min_1.1.0.js"></script>
        <script src="//cdn2.partsim.com/static/js/library/highcharts_4.1.5/highcharts.js"></script>
        <script src="//cdn2.partsim.com/static/js/library/highcharts_4.1.5/modules/exporting.js"></script>
        <script src="//cdn2.partsim.com/static/js/library/highslide_4.1.13/highslide-full.packed.js"></script>
        <script src="//cdn2.partsim.com/static/js/library/underscore-1.8.3.min.js"></script>
        <script src="//cdn2.partsim.com/static/js/library/velocity.min.js"></script>

        <script src="//cdn2.partsim.com/static/js/library/splitter_1.51.js"></script>
        <script src="//cdn2.partsim.com/static/js/library/jpicker-1.1.6.min.js"></script>
        <script src="//cdn2.partsim.com/static/js/library/jquery.download.js"></script>
        <script src="//cdn2.partsim.com/static/js/library/jquery.imgpreload.min.js"></script>

        <script src="//cdn2.partsim.com/static/js/library/jquery.dataTables.min.js"></script>
        <script src="//cdn2.partsim.com/static/js/library/jquery.jeditable.js"></script>
        <script src="//cdn2.partsim.com/static/js/library/jquery.form.js"></script>
        <script src="//cdn2.partsim.com/static/js/library/jquery.dataTables.editable.js"></script>
        <script src="//cdn2.partsim.com/static/js/library/jquery.validate.min.js"></script>

        <script src="//cdn2.partsim.com/static/js/library/json2.js"></script>
        <script src="//cdn2.partsim.com/static/js/library/jquery.cookie.js"></script>

        <script src="//cdn2.partsim.com/static/js/library/sanitizer.min.js"></script>

        <script src="//cdn2.partsim.com/static/js/library/async.js"></script>

        
            <script src="//cdn2.partsim.com/static/js/library/log4javascript_production.js"></script>
        

        <script src="//cdn2.partsim.com/static/js/library/raven_3.9.1/raven.min.js"></script>
        <script type="text/javascript">var sentryOptions={logger:"javascript",whitelistUrls:['https://cdn2.partsim.com'],fetchContext:true,linesOfContext:20,release:'0.33.1'};Raven.config('https://3a5673f739c24c789a6f432bba5ad218@sentry.io/129481',sentryOptions).install();if(_.isEmpty('${loggedInId}')){Raven.setUserContext();}else{Raven.setUserContext({name:'Welcome Guest',email:'',id:'None'});}</script>

        <script type="text/javascript">hs.graphicsDir="//cdn2.partsim.com/static/js/library/highslide_4.1.13/graphics/";var eeServerData=eeServerData||{};console.log("Loading defaults from server");eeServerData.adminUser="False";eeServerData.buildType="PROD";eeServerData.showPopup=false;if("False"==='1'){eeServerData.showPopup=true;}
eeServerData.language="en";eeServerData.sess_language="en";eeServerData.loadProject="";eeServerData.loggedInName="Welcome Guest";eeServerData.loggedInId="None";eeServerData.loggedInEmail="";eeServerData.userInfo={};eeServerData.disableStaticLoading=true;eeServerData.vendorDomainName="www.arrow.com";eeServerData.language="en";eeServerData.customerReference="Partsim Project";eeServerData.useExportServer='True';eeServerData.cdnComponentsPath="//cdn2.partsim.com/static/components/";eeServerData.specificManufacturerName="";eeServerData.serverPolling=10000;eeServerData.s3cdnPath="//component-server-site-media.s3.amazonaws.com/";eeServerData.proxyS3cdnPath="//component-server-site-media.s3.amazonaws.com/";arrowManufacturerList=[];arrowApi={cart:"//components.schematics.com/arrow/cart/",pricing:"//components.schematics.com/arrow/pricing/",partId:"//components.schematics.com/arrow/arrow_ids/",manufacturers:"//components.schematics.com/arrow/manufacturers/",bom:"https://design.arrow.com/bom/v2/"};console.log("Loading defaults from server done");</script>


        <!-- properties sidebar -->
        <script src="/static/js/properties-sidebar-1.0.7.min.js" charset="utf-8"></script>


        <!-- Add i18n internationalization -->
        <script src="//cdn2.partsim.com/static/js/library/i18next-1.5.10.js"></script>
        <script src="/static/js/resources/paramset.js" charset="utf-8"></script>

        <script src="//cdn2.partsim.com/production/0.33.1/deploy/static/js/sim_lang_en.js" charset="utf-8"></script>
        <script src="//cdn2.partsim.com/production/0.33.1/deploy/static/mxgraph/js/mxClient.min.js"></script>
        <script src="//cdn2.partsim.com/production/0.33.1/deploy/static/js/simClient.min.js"></script>

        <!--Searchable Sidebar-->
        <script src="//cdn2.partsim.com/static/js/library/searchable-sidebar-partsim-1.3.3/searchable-sidebar-partsim.min.js" charset="utf-8"></script>

        <!-- Sidebar Ad -->
        <script src="//www.googletagservices.com/tag/js/gpt.js" async></script>
        <script type="text/javascript">
            var googletag = googletag || {};

            googletag.cmd = googletag.cmd || [];
            googletag.cmd.push(function () {
                googletag.defineSlot('/74317539/PartSim', [[300, 250], [300, 300]], 'ad-content').addService(googletag.pubads());
                googletag.pubads().enableSingleRequest();
                googletag.enableServices();
            });
        </script>
	<script src="https://files.carbonpay.app/carbon_embed.bundle.js" handle="part_sim"></script>
    </body>
</html>
