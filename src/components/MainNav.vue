<template>
    <div>
        <nav class="navbar shadow px-2 py-0 navbar-light bg-light navbar-expand-lg" >
            <a href="#" target="_self" class="navbar-brand order-0 nuxt-link-active">
                <img src="../assets/logo.png" height="60" class="">
            </a> <!---->
            <div id="nav-collapse" class="order-4 order-md-1 navbar-collapse collapse d-flex justify-content-end" style="display:none;"><!---->
                <ul class="navbar-nav ml-md-auto align-items-md-center">
                    <div class="d-md-flex pl-3 p-md-none">
                        <li class="nav-item mr-md-2 text-truncate">
                            <a href="/es/empleos" aria-current="page" target="_self" class="nav-link active nuxt-link-active">Jobs</a>
                        </li>
                        <li class="nav-item mr-md-2 text-truncate">
                            <a href="/es/bootcamp-fullstack" target="_self" class="nav-link">Bootcamp</a>
                        </li>
                        <li class="nav-item mr-md-2 text-truncate">
                            <a href="/es/sobre-nosotros" target="_self" class="nav-link">About us</a>
                        </li>
                        <li class="nav-item b-nav-dropdown dropdown mr-md-2 main-nav-dropdown" id="__BVID__44"> <!--mirar id-->
                            <a role="button" aria-haspopup="true" aria-expanded="false" href="#" target="_self" class="nav-link dropdown-toggle" id="__BVID__44__BV_toggle_" aria-controls="__BVID__44__BV_toggle_menu_">
                                <span>For professionals</span>
                            </a>
                            <ul tabindex="-1" class="dropdown-menu p-2 dropdown-menu-right" aria-labelledby="__BVID__44__BV_toggle_" id="__BVID__44__BV_toggle_menu_">
                                <li role="presentation" class="mb-1"> <!--vfor-->
                                    <a role="menuitem" href="#" target="_self" class="dropdown-item">Home</a>
                                </li>
                                <li role="presentation" class="mb-1">
                                    <a role="menuitem" href="#" target="_self" class="dropdown-item">Jobs</a>
                                </li>
                                <li role="presentation" class="mb-1">
                                    <a role="menuitem" href="#" target="_self" class="dropdown-item">Courses and challenges</a>
                                </li>
                                <li role="presentation" class="mb-1">
                                    <a role="menuitem" href="#" target="_self" class="dropdown-item">Questions</a>
                                </li>
                                <li role="presentation" class="mb-1">
                                    <a role="menuitem" href="#" target="_self" class="dropdown-item">Teachers</a>
                                </li>
                                <li role="presentation" class="mb-1">
                                    <a role="menuitem" href="#" target="_self" class="dropdown-item">Bootcamp</a>
                                </li>
                                
                            </ul>
                        </li>
                        <li class="nav-item b-nav-dropdown dropdown mr-md-2 main-nav-dropdown" id="__BVID__58">
                            <a role="button" aria-haspopup="true" aria-expanded="false" href="#" target="_self" class="nav-link dropdown-toggle" id="__BVID__58__BV_toggle_" aria-controls="__BVID__58__BV_toggle_menu_">
                                <span>For companies</span>
                            </a>
                            <ul tabindex="-1" class="dropdown-menu p-2 dropdown-menu-right" aria-labelledby="__BVID__58__BV_toggle_" id="__BVID__58__BV_toggle_menu_">
                                <li role="presentation" class="mb-1">
                                    <a role="menuitem" href="#" target="_self" class="dropdown-item">Home</a>
                                </li>
                                <li role="presentation" class="mb-1">
                                    <a role="menuitem" href="#" target="_self" class="dropdown-item">Post job</a>
                                </li>
                                <li role="presentation" class="mb-1">
                                    <a role="menuitem" href="#" target="_self" class="dropdown-item">Our process</a>
                                </li>
                                <li role="presentation" class="mb-1">
                                    <a role="menuitem" href="#" target="_self" class="dropdown-item">Prices</a>
                                </li>
                                <li role="presentation" class="mb-1">
                                    <a role="menuitem" href="#" target="_self" class="dropdown-item">Online Tests</a>
                                </li>
                                <li role="presentation" class="mb-1">
                                    <a role="menuitem" href="#" target="_self" class="dropdown-item">Payroll</a>
                                </li>
                                <li role="presentation" class="mb-1">
                                    <a role="menuitem" href="#" target="_self" class="dropdown-item">Blog</a>
                                </li>
                                <li role="presentation" class="mb-1">
                                    <a role="menuitem" href="#" target="_self" class="dropdown-item">Comercial</a>
                                </li>
                                <li role="presentation" class="mb-1">
                                    <a role="menuitem" href="#" target="_self" class="dropdown-item">Salary Calculator</a>
                                </li>
                            </ul>
                        </li>
                    </div>
                    <div class="w-100 px-2 m-0 p-0 mr-2 text-truncate">
                        <li class="nav-item btn btn-outline-light btn-sm border" style="list-style: none;">
                            <a href="#" target="_self" class="nav-link" role="button">
                                <div class="d-flex align-items-center justify-content-center">
                                    <svg viewBox="0 0 16 16" width="1em" height="1em" focusable="false" role="img" aria-label="globe" xmlns="http://www.w3.org/2000/svg" fill="currentColor" class="bi-globe mr-1 b-icon bi" style="font-size: 120%;">
                                        <g>
                                            <path d="M0 8a8 8 0 1 1 16 0A8 8 0 0 1 0 8zm7.5-6.923c-.67.204-1.335.82-1.887 1.855A7.97 7.97 0 0 0 5.145 4H7.5V1.077zM4.09 4a9.267 9.267 0 0 1 .64-1.539 6.7 6.7 0 0 1 .597-.933A7.025 7.025 0 0 0 2.255 4H4.09zm-.582 3.5c.03-.877.138-1.718.312-2.5H1.674a6.958 6.958 0 0 0-.656 2.5h2.49zM4.847 5a12.5 12.5 0 0 0-.338 2.5H7.5V5H4.847zM8.5 5v2.5h2.99a12.495 12.495 0 0 0-.337-2.5H8.5zM4.51 8.5a12.5 12.5 0 0 0 .337 2.5H7.5V8.5H4.51zm3.99 0V11h2.653c.187-.765.306-1.608.338-2.5H8.5zM5.145 12c.138.386.295.744.468 1.068.552 1.035 1.218 1.65 1.887 1.855V12H5.145zm.182 2.472a6.696 6.696 0 0 1-.597-.933A9.268 9.268 0 0 1 4.09 12H2.255a7.024 7.024 0 0 0 3.072 2.472zM3.82 11a13.652 13.652 0 0 1-.312-2.5h-2.49c.062.89.291 1.733.656 2.5H3.82zm6.853 3.472A7.024 7.024 0 0 0 13.745 12H11.91a9.27 9.27 0 0 1-.64 1.539 6.688 6.688 0 0 1-.597.933zM8.5 12v2.923c.67-.204 1.335-.82 1.887-1.855.173-.324.33-.682.468-1.068H8.5zm3.68-1h2.146c.365-.767.594-1.61.656-2.5h-2.49a13.65 13.65 0 0 1-.312 2.5zm2.802-3.5a6.959 6.959 0 0 0-.656-2.5H12.18c.174.782.282 1.623.312 2.5h2.49zM11.27 2.461c.247.464.462.98.64 1.539h1.835a7.024 7.024 0 0 0-3.072-2.472c.218.284.418.598.597.933zM10.855 4a7.966 7.966 0 0 0-.468-1.068C9.835 1.897 9.17 1.282 8.5 1.077V4h2.355z"></path>
                                        </g>
                                    </svg> 
                                    <span>Spanish</span>
                                </div>
                            </a></li> <!---->
                    </div>
                </ul>
            </div>
            <div class="order-2 d-flex align-items-center">
                <div class="mr-2 d-flex col-7">
                    <button type="button" class="btn d-inline-block position-relative btn-light border-secondary collapsed" aria-expanded="false" aria-controls="notifications-sidebar" style="overflow-anchor: none;">
                        <svg viewBox="0 0 16 16" width="1em" height="1em" focusable="false" role="img" aria-label="bell" xmlns="http://www.w3.org/2000/svg" fill="currentColor" class="bi-bell b-icon bi">
                            <g>
                                <path d="M8 16a2 2 0 0 0 2-2H6a2 2 0 0 0 2 2zM8 1.918l-.797.161A4.002 4.002 0 0 0 4 6c0 .628-.134 2.197-.459 3.742-.16.767-.376 1.566-.663 2.258h10.244c-.287-.692-.502-1.49-.663-2.258C12.134 8.197 12 6.628 12 6a4.002 4.002 0 0 0-3.203-3.92L8 1.917zM14.22 12c.223.447.481.801.78 1H1c.299-.199.557-.553.78-1C2.68 10.2 3 6.88 3 6c0-2.42 1.72-4.44 4.005-4.901a1 1 0 1 1 1.99 0A5.002 5.002 0 0 1 13 6c0 .88.32 4.2 1.22 6z"></path>
                            </g>
                        </svg> <!---->
                    </button>
                    <div tabindex="-1" class="b-sidebar-outer"><!---->
                        <div id="notifications-sidebar" tabindex="-1" role="dialog" aria-modal="true" aria-hidden="true" aria-labelledby="notifications-sidebar___title__" class="b-sidebar shadow b-sidebar-right bg-light text-dark" style="display: none;">
                            <header class="b-sidebar-header">
                                <button type="button" aria-label="Close" class="close text-dark">
                                    <svg viewBox="0 0 16 16" width="1em" height="1em" focusable="false" role="img" aria-label="x" xmlns="http://www.w3.org/2000/svg" fill="currentColor" class="bi-x b-icon bi">
                                        <g>
                                            <path d="M4.646 4.646a.5.5 0 0 1 .708 0L8 7.293l2.646-2.647a.5.5 0 0 1 .708.708L8.707 8l2.647 2.646a.5.5 0 0 1-.708.708L8 8.707l-2.646 2.647a.5.5 0 0 1-.708-.708L7.293 8 4.646 5.354a.5.5 0 0 1 0-.708z"></path>
                                        </g>
                                    </svg>
                                    </button>
                                    <strong id="notifications-sidebar___title__">Notifications</strong>
                            </header>
                            <div class="b-sidebar-body notifications-list custom-scroll">
                                <div class="px-2">
                                    <nav class="mb-3">
                                        <ul class="nav flex-column">
                                            <button type="button" class="btn p-0 btn-link btn-sm" style="font-size: 0.8em;">Update</button>
                                            <div style="display: none;">
                                                <div class="px-5 pb-5">
                                                    <div class="d-flex flex-column justify-content-center align-items-center">
                                                        <div class="peaku-pulse-loader">
                                                            <div class="loader-segments">
                                                                <div></div>
                                                                <div></div>
                                                                <div></div>
                                                            </div>
                                                        </div>
                                                        <div class="loader-text">Loading</div>
                                                    </div>
                                                </div>
                                            </div> 
                                            <img src="/gif/no-notifications.gif" class=""> <!---->
                                        </ul>
                                    </nav>
                                </div>
                            </div><!---->
                        </div><!---->
                        <div class="b-sidebar-backdrop bg-dark" style="display: none;"></div>
                    </div>
                </div>
                <div>
                    <div><!----> <!----> 
                        <a href="#" class="btn mr-2 px-3 btn-success d-none" id="sign-up-btn" target="_self">
                            See candidates
                        </a>
                        <div class="dropdown b-dropdown order-2 profile-dropdown btn-group" title="Juan Felipe López Castaño" id="__BVID__168"><!---->
                            <button aria-haspopup="menu" aria-expanded="false" type="button" id="__BVID__168__BV_toggle_">
                                <div class="d-flex align-items-center justify-content-center" style="font-size: 0.7em;">
                                    <span class="b-avatar badge-dark rounded-circle d-flex align-items-center justify-content-center" lazy="" style="width: 1.8rem; height: 1.8rem;">
                                        <span class="b-avatar-img">
                                            <img class="b-avatar-image" src="../assets/Juan_photo.png" alt="avatar">
                                        </span><!----></span>
                                    
                                </div>
                            </button>
                        
                        </div>
                </div>
                <div id="auth-modal___BV_modal_outer_" style="position: absolute; z-index: 1040;">
                    <div id="auth-modal" role="dialog" aria-hidden="true" aria-labelledby="auth-modal___BV_modal_title_" aria-describedby="auth-modal___BV_modal_body_" class="modal fade" style="display: none;">
                        <div class="modal-dialog modal-md modal-dialog-centered"><!---->
                            <div id="auth-modal___BV_modal_content_" tabindex="-1" class="modal-content">
                                <header id="auth-modal___BV_modal_header_" class="modal-header bg-blue">
                                    <h5 id="auth-modal___BV_modal_title_" class="modal-title"><!---->
                                        Register to apply for jobs
                                    </h5>
                                    <button type="button" aria-label="Close" class="close">×</button>
                                </header>
                                <div id="auth-modal___BV_modal_body_" class="modal-body p-md-4"> <!---->
                                    <section id="auth-options" class="mb-3 w-100">
                                        <div class="spam-animation mb-2 animated">
                                            <span class="b-avatar badge-secondary rounded-circle" style="width: 6em; height: 6em;">
                                                <svg viewBox="0 0 16 16" width="1em" height="1em" focusable="false" role="img" aria-label="envelope" aria-hidden="true" alt="avatar" xmlns="http://www.w3.org/2000/svg" fill="currentColor" class="bi-envelope b-icon bi">
                                                    <g>
                                                        <path d="M0 4a2 2 0 0 1 2-2h12a2 2 0 0 1 2 2v8a2 2 0 0 1-2 2H2a2 2 0 0 1-2-2V4zm2-1a1 1 0 0 0-1 1v.217l7 4.2 7-4.2V4a1 1 0 0 0-1-1H2zm13 2.383-4.758 2.855L15 11.114v-5.73zm-.034 6.878L9.271 8.82 8 9.583 6.728 8.82l-5.694 3.44A1 1 0 0 0 2 13h12a1 1 0 0 0 .966-.739zM1 11.114l4.758-2.876L1 5.383v5.73z"></path>
                                                    </g>
                                                </svg><!---->
                                            </span> 
                                            <span class="b-avatar badge-secondary rounded-circle" style="width: 6em; height: 6em;">
                                                <span class="b-avatar-img">
                                                    <img src="/img/login/profile.png" alt="avatar">
                                                </span><!---->
                                            </span>
                                        </div>
                                        <h5 class="text-center mb-5">We do not send spam</h5> 
                                        <button id="google-signin-btn-0" type="button" class="btn btn-block btn-outline-secondary mt-2 mb-3">
                                            <img src="/icon/logos/google.svg" width="25" class=""> Register with google
                                        </button> 
                                        <a href="#" class="text-center d-block text-info">Register with your own email</a>
                                        <div class="mt-5 text-center custom-control custom-checkbox">
                                            <input type="checkbox" class="custom-control-input" value="true" id="__BVID__162">
                                            <label class="custom-control-label" for="__BVID__162">
                                                Receive new offers and notifications
                                            </label>
                                        </div>
                                        <form id="auth-form" style="display: none;">
                                            <fieldset class="form-group mini-label mb-4" id="__BVID__163">
                                                <legend tabindex="-1" class="bv-no-focus-ring col-form-label pt-0" id="__BVID__163__BV_label_">Email</legend>
                                                <div>
                                                    <input name="email" type="email" required="required" aria-required="true" class="form-control" id="__BVID__164"><!----><!----><!---->
                                                </div>
                                            </fieldset>
                                            <div role="group" class="form-group mini-label" id="__BVID__165">
                                                <label for="password" class="d-block" id="__BVID__165__BV_label_">Password</label>
                                                <div>
                                                    <div role="group" class="input-group"><!----> 
                                                        <input id="password" name="password" type="password" required="required" aria-required="true" class="form-control">
                                                        <div class="input-group-append">
                                                            <div class="input-group-text cursor-pointer">
                                                                <svg viewBox="0 0 16 16" width="1em" height="1em" focusable="false" role="img" aria-label="eye" xmlns="http://www.w3.org/2000/svg" fill="currentColor" class="bi-eye b-icon bi">
                                                                    <g>
                                                                        <path d="M16 8s-3-5.5-8-5.5S0 8 0 8s3 5.5 8 5.5S16 8 16 8zM1.173 8a13.133 13.133 0 0 1 1.66-2.043C4.12 4.668 5.88 3.5 8 3.5c2.12 0 3.879 1.168 5.168 2.457A13.133 13.133 0 0 1 14.828 8c-.058.087-.122.183-.195.288-.335.48-.83 1.12-1.465 1.755C11.879 11.332 10.119 12.5 8 12.5c-2.12 0-3.879-1.168-5.168-2.457A13.134 13.134 0 0 1 1.172 8z"></path>
                                                                        <path d="M8 5.5a2.5 2.5 0 1 0 0 5 2.5 2.5 0 0 0 0-5zM4.5 8a3.5 3.5 0 1 1 7 0 3.5 3.5 0 0 1-7 0z"></path>
                                                                    </g>
                                                                </svg>
                                                            </div>
                                                        </div>
                                                    </div><!----><!----><!---->
                                                </div>
                                            </div> <!----> 
                                            <button type="submit" class="btn my-4 btn-info btn-block">
                                                <svg viewBox="0 0 16 16" width="1em" height="1em" focusable="false" role="img" aria-label="envelope" xmlns="http://www.w3.org/2000/svg" fill="currentColor" class="bi-envelope b-icon bi">
                                                    <g>
                                                        <path d="M0 4a2 2 0 0 1 2-2h12a2 2 0 0 1 2 2v8a2 2 0 0 1-2 2H2a2 2 0 0 1-2-2V4zm2-1a1 1 0 0 0-1 1v.217l7 4.2 7-4.2V4a1 1 0 0 0-1-1H2zm13 2.383-4.758 2.855L15 11.114v-5.73zm-.034 6.878L9.271 8.82 8 9.583 6.728 8.82l-5.694 3.44A1 1 0 0 0 2 13h12a1 1 0 0 0 .966-.739zM1 11.114l4.758-2.876L1 5.383v5.73z"></path>
                                                    </g>
                                                </svg>
                                                Register with email
                                            </button>
                                        </form>
                                    </section>
                                </div>
                                <footer id="auth-modal___BV_modal_footer_" class="modal-footer justify-content-center">
                                    <div>
                                        Do you already have an account?
                                        <button type="button" class="btn btn-link text-info">Log in</button>
                                    </div>
                                </footer>
                            </div><!---->
                        </div>
                    </div><!---->
                </div> <!---->
                </div>
            </div> 
        <button type="button" aria-label="Toggle navigation" class="navbar-toggler d-none collapsed" aria-expanded="false" aria-controls="nav-collapse" style="overflow-anchor: none;">
            <span class="navbar-toggler-icon"></span>
        </button>
    </nav>
    <nav class="navbar shadow-2 border-top fixed-bottom p-0 d-md-none navbar-light bg-light navbar-expand">
        <ul class="navbar-nav d-flex justify-content-between align-items-center w-100 mobile-nav">
            <li class="nav-item text-truncate">
                <a href="#" aria-current="page" class="nav-link active nuxt-link-active" target="_self">
                <svg viewBox="0 0 16 16" width="1em" height="1em" focusable="false" role="img" aria-label="briefcase" xmlns="http://www.w3.org/2000/svg" fill="currentColor" class="bi-briefcase b-icon bi" style="font-size: 150%;">
                        <g>
                            <path d="M6.5 1A1.5 1.5 0 0 0 5 2.5V3H1.5A1.5 1.5 0 0 0 0 4.5v8A1.5 1.5 0 0 0 1.5 14h13a1.5 1.5 0 0 0 1.5-1.5v-8A1.5 1.5 0 0 0 14.5 3H11v-.5A1.5 1.5 0 0 0 9.5 1h-3zm0 1h3a.5.5 0 0 1 .5.5V3H6v-.5a.5.5 0 0 1 .5-.5zm1.886 6.914L15 7.151V12.5a.5.5 0 0 1-.5.5h-13a.5.5 0 0 1-.5-.5V7.15l6.614 1.764a1.5 1.5 0 0 0 .772 0zM1.5 4h13a.5.5 0 0 1 .5.5v1.616L8.129 7.948a.5.5 0 0 1-.258 0L1 6.116V4.5a.5.5 0 0 1 .5-.5z"></path>
                        </g>
                    </svg> 
                    <span>Jobs</span>
                </a>
            </li>
            <li class="nav-item text-truncate"><a href="#" class="nav-link" target="_self">
                <svg viewBox="0 0 16 16" width="1em" height="1em" focusable="false" role="img" aria-label="file earmark check" xmlns="http://www.w3.org/2000/svg" fill="currentColor" class="bi-file-earmark-check b-icon bi" style="font-size: 150%;">
                        <g>
                            <path d="M10.854 7.854a.5.5 0 0 0-.708-.708L7.5 9.793 6.354 8.646a.5.5 0 1 0-.708.708l1.5 1.5a.5.5 0 0 0 .708 0l3-3z"></path>
                            <path d="M14 14V4.5L9.5 0H4a2 2 0 0 0-2 2v12a2 2 0 0 0 2 2h8a2 2 0 0 0 2-2zM9.5 3A1.5 1.5 0 0 0 11 4.5h2V14a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1V2a1 1 0 0 1 1-1h5.5v2z"></path>
                        </g>
                    </svg> 
                    <span>Applications</span>
                </a>
            </li>
            <li class="nav-item text-truncate">
                <a href="#" class="nav-link" target="_self">
                    <svg viewBox="0 0 16 16" width="1em" height="1em" focusable="false" role="img" aria-label="controller" xmlns="http://www.w3.org/2000/svg" fill="currentColor" class="bi-controller b-icon bi" style="font-size: 150%;">
                        <g>
                            <path d="M11.5 6.027a.5.5 0 1 1-1 0 .5.5 0 0 1 1 0zm-1.5 1.5a.5.5 0 1 0 0-1 .5.5 0 0 0 0 1zm2.5-.5a.5.5 0 1 1-1 0 .5.5 0 0 1 1 0zm-1.5 1.5a.5.5 0 1 0 0-1 .5.5 0 0 0 0 1zm-6.5-3h1v1h1v1h-1v1h-1v-1h-1v-1h1v-1z"></path>
                            <path d="M3.051 3.26a.5.5 0 0 1 .354-.613l1.932-.518a.5.5 0 0 1 .62.39c.655-.079 1.35-.117 2.043-.117.72 0 1.443.041 2.12.126a.5.5 0 0 1 .622-.399l1.932.518a.5.5 0 0 1 .306.729c.14.09.266.19.373.297.408.408.78 1.05 1.095 1.772.32.733.599 1.591.805 2.466.206.875.34 1.78.364 2.606.024.816-.059 1.602-.328 2.21a1.42 1.42 0 0 1-1.445.83c-.636-.067-1.115-.394-1.513-.773-.245-.232-.496-.526-.739-.808-.126-.148-.25-.292-.368-.423-.728-.804-1.597-1.527-3.224-1.527-1.627 0-2.496.723-3.224 1.527-.119.131-.242.275-.368.423-.243.282-.494.575-.739.808-.398.38-.877.706-1.513.773a1.42 1.42 0 0 1-1.445-.83c-.27-.608-.352-1.395-.329-2.21.024-.826.16-1.73.365-2.606.206-.875.486-1.733.805-2.466.315-.722.687-1.364 1.094-1.772a2.34 2.34 0 0 1 .433-.335.504.504 0 0 1-.028-.079zm2.036.412c-.877.185-1.469.443-1.733.708-.276.276-.587.783-.885 1.465a13.748 13.748 0 0 0-.748 2.295 12.351 12.351 0 0 0-.339 2.406c-.022.755.062 1.368.243 1.776a.42.42 0 0 0 .426.24c.327-.034.61-.199.929-.502.212-.202.4-.423.615-.674.133-.156.276-.323.44-.504C4.861 9.969 5.978 9.027 8 9.027s3.139.942 3.965 1.855c.164.181.307.348.44.504.214.251.403.472.615.674.318.303.601.468.929.503a.42.42 0 0 0 .426-.241c.18-.408.265-1.02.243-1.776a12.354 12.354 0 0 0-.339-2.406 13.753 13.753 0 0 0-.748-2.295c-.298-.682-.61-1.19-.885-1.465-.264-.265-.856-.523-1.733-.708-.85-.179-1.877-.27-2.913-.27-1.036 0-2.063.091-2.913.27z"></path>
                        </g>
                    </svg> 
                    <span>CodeX</span>
                </a>
            </li>
            <li class="nav-item text-truncate" style="display: none;">
                <a href="#" class="nav-link" target="_self">
                    <svg viewBox="0 0 16 16" width="1em" height="1em" focusable="false" role="img" aria-label="briefcase" xmlns="http://www.w3.org/2000/svg" fill="currentColor" class="bi-briefcase b-icon bi" style="font-size: 150%;">
                        <g>
                            <path d="M6.5 1A1.5 1.5 0 0 0 5 2.5V3H1.5A1.5 1.5 0 0 0 0 4.5v8A1.5 1.5 0 0 0 1.5 14h13a1.5 1.5 0 0 0 1.5-1.5v-8A1.5 1.5 0 0 0 14.5 3H11v-.5A1.5 1.5 0 0 0 9.5 1h-3zm0 1h3a.5.5 0 0 1 .5.5V3H6v-.5a.5.5 0 0 1 .5-.5zm1.886 6.914L15 7.151V12.5a.5.5 0 0 1-.5.5h-13a.5.5 0 0 1-.5-.5V7.15l6.614 1.764a1.5 1.5 0 0 0 .772 0zM1.5 4h13a.5.5 0 0 1 .5.5v1.616L8.129 7.948a.5.5 0 0 1-.258 0L1 6.116V4.5a.5.5 0 0 1 .5-.5z"></path>
                        </g>
                    </svg> 
                    <span>Current job</span>
                </a>
            </li>
            <li class="nav-item text-truncate">
                <a href="#" class="nav-link" target="_self">
                    <svg viewBox="0 0 16 16" width="1em" height="1em" focusable="false" role="img" aria-label="file earmark person" xmlns="http://www.w3.org/2000/svg" fill="currentColor" class="bi-file-earmark-person b-icon bi" style="font-size: 150%;">
                        <g>
                            <path d="M11 8a3 3 0 1 1-6 0 3 3 0 0 1 6 0z"></path>
                            <path d="M14 14V4.5L9.5 0H4a2 2 0 0 0-2 2v12a2 2 0 0 0 2 2h8a2 2 0 0 0 2-2zM9.5 3A1.5 1.5 0 0 0 11 4.5h2v9.255S12 12 8 12s-5 1.755-5 1.755V2a1 1 0 0 1 1-1h5.5v2z"></path>
                        </g>
                    </svg> 
                    <span>Profile</span>
                </a>
            </li>
            <li class="nav-item text-truncate" style="display: none;">
                <a href="#" class="nav-link" target="_self">
                    <svg viewBox="0 0 16 16" width="1em" height="1em" focusable="false" role="img" aria-label="braces" xmlns="http://www.w3.org/2000/svg" fill="currentColor" class="bi-braces b-icon bi" style="font-size: 150%;">
                        <g>
                            <path d="M2.114 8.063V7.9c1.005-.102 1.497-.615 1.497-1.6V4.503c0-1.094.39-1.538 1.354-1.538h.273V2h-.376C3.25 2 2.49 2.759 2.49 4.352v1.524c0 1.094-.376 1.456-1.49 1.456v1.299c1.114 0 1.49.362 1.49 1.456v1.524c0 1.593.759 2.352 2.372 2.352h.376v-.964h-.273c-.964 0-1.354-.444-1.354-1.538V9.663c0-.984-.492-1.497-1.497-1.6zM13.886 7.9v.163c-1.005.103-1.497.616-1.497 1.6v1.798c0 1.094-.39 1.538-1.354 1.538h-.273v.964h.376c1.613 0 2.372-.759 2.372-2.352v-1.524c0-1.094.376-1.456 1.49-1.456V7.332c-1.114 0-1.49-.362-1.49-1.456V4.352C13.51 2.759 12.75 2 11.138 2h-.376v.964h.273c.964 0 1.354.444 1.354 1.538V6.3c0 .984.492 1.497 1.497 1.6z"></path>
                        </g>
                    </svg> 
                    <span>Bootcamp</span>
                </a>
            </li>
            <li class="nav-item text-truncate" style="display: none;">
                <a href="#" class="nav-link nuxt-link-active" target="_self">
                    <svg viewBox="0 0 16 16" width="1em" height="1em" focusable="false" role="img" aria-label="building" xmlns="http://www.w3.org/2000/svg" fill="currentColor" class="bi-building b-icon bi" style="font-size: 150%;">
                        <g>
                            <path fill-rule="evenodd" d="M14.763.075A.5.5 0 0 1 15 .5v15a.5.5 0 0 1-.5.5h-3a.5.5 0 0 1-.5-.5V14h-1v1.5a.5.5 0 0 1-.5.5h-9a.5.5 0 0 1-.5-.5V10a.5.5 0 0 1 .342-.474L6 7.64V4.5a.5.5 0 0 1 .276-.447l8-4a.5.5 0 0 1 .487.022zM6 8.694 1 10.36V15h5V8.694zM7 15h2v-1.5a.5.5 0 0 1 .5-.5h2a.5.5 0 0 1 .5.5V15h2V1.309l-7 3.5V15z"></path>
                            <path d="M2 11h1v1H2v-1zm2 0h1v1H4v-1zm-2 2h1v1H2v-1zm2 0h1v1H4v-1zm4-4h1v1H8V9zm2 0h1v1h-1V9zm-2 2h1v1H8v-1zm2 0h1v1h-1v-1zm2-2h1v1h-1V9zm0 2h1v1h-1v-1zM8 7h1v1H8V7zm2 0h1v1h-1V7zm2 0h1v1h-1V7zM8 5h1v1H8V5zm2 0h1v1h-1V5zm2 0h1v1h-1V5zm0-2h1v1h-1V3z"></path>
                        </g>
                    </svg> <span>For companies</span></a></li>
            <li class="nav-item collapsed" role="button" tabindex="0" aria-expanded="false" aria-controls="mobile-sidebar" style="overflow-anchor: none;">
                <a data-v-2bce2f79="" href="#" target="_self" class="nav-link">
                    <svg data-v-2bce2f79="" viewBox="0 0 16 16" width="1em" height="1em" focusable="false" role="img" aria-label="three dots" xmlns="http://www.w3.org/2000/svg" fill="currentColor" class="bi-three-dots b-icon bi" style="font-size: 150%;">
                        <g>
                            <path d="M3 9.5a1.5 1.5 0 1 1 0-3 1.5 1.5 0 0 1 0 3zm5 0a1.5 1.5 0 1 1 0-3 1.5 1.5 0 0 1 0 3zm5 0a1.5 1.5 0 1 1 0-3 1.5 1.5 0 0 1 0 3z"></path>
                        </g>
                    </svg> 
                    <span> More content </span>
                </a>
            </li>
        </ul>
        <div tabindex="-1" class="b-sidebar-outer mobile-sidebar"><!---->
            <div id="mobile-sidebar" tabindex="-1" role="dialog" aria-modal="true" aria-hidden="true" aria-labelledby="mobile-sidebar___title__" class="b-sidebar shadow b-sidebar-right bg-light text-dark" style="display: none;">
                <header class="b-sidebar-header">
                    <button type="button" aria-label="Close" class="close text-dark">
                        <svg viewBox="0 0 16 16" width="1em" height="1em" focusable="false" role="img" aria-label="x" xmlns="http://www.w3.org/2000/svg" fill="currentColor" class="bi-x b-icon bi">
                            <g>
                                <path d="M4.646 4.646a.5.5 0 0 1 .708 0L8 7.293l2.646-2.647a.5.5 0 0 1 .708.708L8.707 8l2.647 2.646a.5.5 0 0 1-.708.708L8 8.707l-2.646 2.647a.5.5 0 0 1-.708-.708L7.293 8 4.646 5.354a.5.5 0 0 1 0-.708z"></path>
                            </g>
                        </svg>
                    </button>
                    <strong id="mobile-sidebar___title__">More options</strong>
                </header>
                <div class="b-sidebar-body">
                    <div class="p-2"><!---->
                        <nav class="mb-3">
                            <ul class="nav flex-column">
                                <li class="nav-item text-truncate text-dark">
                                    <a href="#" class="nav-link text-dark" target="_self">
                                        <svg viewBox="0 0 16 16" width="1em" height="1em" focusable="false" role="img" aria-label="blank" xmlns="http://www.w3.org/2000/svg" fill="currentColor" class="bi-blank b-icon bi">
                                            <g></g>
                                        </svg>
                                        Teachers
                                    </a>
                                </li>
                                <li class="nav-item text-truncate text-dark">
                                    <a href="#" class="nav-link text-dark" target="_self">
                                        <svg viewBox="0 0 16 16" width="1em" height="1em" focusable="false" role="img" aria-label="blank" xmlns="http://www.w3.org/2000/svg" fill="currentColor" class="bi-blank b-icon bi">
                                            <g></g>
                                        </svg>
                                        Questions
                                    </a>
                                </li>
                                <li class="nav-item text-truncate text-dark">
                                    <a href="/es/blog" class="nav-link text-dark" target="_self">
                                        <svg viewBox="0 0 16 16" width="1em" height="1em" focusable="false" role="img" aria-label="blank" xmlns="http://www.w3.org/2000/svg" fill="currentColor" class="bi-blank b-icon bi">
                                            <g></g>
                                        </svg>
                                        Blog
                                    </a></li>
                                <li class="nav-item text-truncate text-dark"><a href="/" class="nav-link nuxt-link-active text-dark" target="_self">
                                    <svg viewBox="0 0 16 16" width="1em" height="1em" focusable="false" role="img" aria-label="building" xmlns="http://www.w3.org/2000/svg" fill="currentColor" class="bi-building b-icon bi">
                                            <g>
                                                <path fill-rule="evenodd" d="M14.763.075A.5.5 0 0 1 15 .5v15a.5.5 0 0 1-.5.5h-3a.5.5 0 0 1-.5-.5V14h-1v1.5a.5.5 0 0 1-.5.5h-9a.5.5 0 0 1-.5-.5V10a.5.5 0 0 1 .342-.474L6 7.64V4.5a.5.5 0 0 1 .276-.447l8-4a.5.5 0 0 1 .487.022zM6 8.694 1 10.36V15h5V8.694zM7 15h2v-1.5a.5.5 0 0 1 .5-.5h2a.5.5 0 0 1 .5.5V15h2V1.309l-7 3.5V15z"></path>
                                                <path d="M2 11h1v1H2v-1zm2 0h1v1H4v-1zm-2 2h1v1H2v-1zm2 0h1v1H4v-1zm4-4h1v1H8V9zm2 0h1v1h-1V9zm-2 2h1v1H8v-1zm2 0h1v1h-1v-1zm2-2h1v1h-1V9zm0 2h1v1h-1v-1zM8 7h1v1H8V7zm2 0h1v1h-1V7zm2 0h1v1h-1V7zM8 5h1v1H8V5zm2 0h1v1h-1V5zm2 0h1v1h-1V5zm0-2h1v1h-1V3z"></path>
                                            </g>
                                        </svg>
                                        For companies
                                    </a></li>
                                <li class="nav-item text-truncate text-dark">
                                    <a href="/es/sobre-nosotros" class="nav-link text-dark" target="_self">
                                        <svg viewBox="0 0 16 16" width="1em" height="1em" focusable="false" role="img" aria-label="blank" xmlns="http://www.w3.org/2000/svg" fill="currentColor" class="bi-blank b-icon bi">
                                            <g></g>
                                        </svg>
                                        About us
                                    </a>
                                </li>
                            </ul>
                        </nav>
                    </div>
                </div><!---->
            </div><!---->
            <div class="b-sidebar-backdrop bg-dark" style="display: none;"></div>
        </div>
    </nav> <!---->
</div></template>

<script>
export default {
    name: 'MainNav',
    /*props: {
        msg: String
    }, */
    data() {
        return {
            navInfo: [
                {
                    img: require("../assets/companies/acg.png"), vacancyName: "Educational technology coordinator",
                    skills: ["Power Bi", "Power Apps", "Microsoft 365"], company: "ACG", workModality: "Remote", salary: "Confidential", vacancies: "1 vacant", publicationDate: "1 day ago"
                },

            ],
        }
    },
    methods: {
    }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<!--single file component con html, script y css-->
<!-- Estilos si es necesario -->
<style scoped>
.b-avatar{
    width: 1.8rem;
    height: 1.8rem;    
}
.b-avatar-image{
    width: 20px;
    height: auto;
}
.b-icon.bi{
    font-size: 125%;
}
.dropdown button{
    border: none;
    outline: none;
}


/* Estilos CSS */
</style>