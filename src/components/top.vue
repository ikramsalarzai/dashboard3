<template>
<div id="wrapper" >
  <div id="page-wrapper" class="gray-bg dashbard-1">
        <div class="row border-bottom">
        <nav class="navbar navbar-static-top" role="navigation" style="margin-bottom: 0">
        <div class="navbar-header">
            <a class="navbar-minimalize minimalize-styl-2 btn btn-primary " href="#"><i class="fa fa-bars"></i> </a>
            <form role="search" class="navbar-form-custom" action="search_results.html">
                <div class="form-group">
                    <input type="text" placeholder="Search for something..." class="form-control" name="top-search" id="top-search">
                </div>
            </form>
        </div>
            <ul class="nav navbar-top-links navbar-right">
                <li>
                    <span class="m-r-sm text-muted welcome-message">Welcome to INSPINIA+ Admin Theme.</span>
                </li>
                <li class="dropdown">
                    <a class="dropdown-toggle count-info" data-toggle="dropdown" href="#">
                        <i class="fa fa-envelope"></i>  <span class="label label-warning">16</span>
                    </a>
                    <ul class="dropdown-menu dropdown-messages">
                        <li>
                            <div class="dropdown-messages-box">
                                <a href="profile.html" class="pull-left">
                                    <img alt="image" class="img-circle" src="img/a7.jpg">
                                </a>
                                <div class="media-body">
                                    <small class="pull-right">46h ago</small>
                                    <strong>Mike Loreipsum</strong> started following <strong>Monica Smith</strong>. <br>
                                    <small class="text-muted">3 days ago at 7:58 pm - 10.06.2014</small>
                                </div>
                            </div>
                        </li>
                        <li class="divider"></li>
                        <li>
                            <div class="dropdown-messages-box">
                                <a href="profile.html" class="pull-left">
                                    <img alt="image" class="img-circle" src="img/a4.jpg">
                                </a>
                                <div class="media-body ">
                                    <small class="pull-right text-navy">5h ago</small>
                                    <strong>Chris Johnatan Overtunk</strong> started following <strong>Monica Smith</strong>. <br>
                                    <small class="text-muted">Yesterday 1:21 pm - 11.06.2014</small>
                                </div>
                            </div>
                        </li>
                        <li class="divider"></li>
                        <li>
                            <div class="dropdown-messages-box">
                                <a href="profile.html" class="pull-left">
                                    <img alt="image" class="img-circle" src="img/profile.jpg">
                                </a>
                                <div class="media-body ">
                                    <small class="pull-right">23h ago</small>
                                    <strong>Monica Smith</strong> love <strong>Kim Smith</strong>. <br>
                                    <small class="text-muted">2 days ago at 2:30 am - 11.06.2014</small>
                                </div>
                            </div>
                        </li>
                        <li class="divider"></li>
                        <li>
                            <div class="text-center link-block">
                                <a href="mailbox.html">
                                    <i class="fa fa-envelope"></i> <strong>Read All Messages</strong>
                                </a>
                            </div>
                        </li>
                    </ul>
                </li>
                <li class="dropdown">
                    <a class="dropdown-toggle count-info" data-toggle="dropdown" href="#">
                        <i class="fa fa-bell"></i>  <span class="label label-primary">8</span>
                    </a>
                    <ul class="dropdown-menu dropdown-alerts">
                        <li>
                            <a href="mailbox.html">
                                <div>
                                    <i class="fa fa-envelope fa-fw"></i> You have 16 messages
                                    <span class="pull-right text-muted small">4 minutes ago</span>
                                </div>
                            </a>
                        </li>
                        <li class="divider"></li>
                        <li>
                            <a href="profile.html">
                                <div>
                                    <i class="fa fa-twitter fa-fw"></i> 3 New Followers
                                    <span class="pull-right text-muted small">12 minutes ago</span>
                                </div>
                            </a>
                        </li>
                        <li class="divider"></li>
                        <li>
                            <a href="grid_options.html">
                                <div>
                                    <i class="fa fa-upload fa-fw"></i> Server Rebooted
                                    <span class="pull-right text-muted small">4 minutes ago</span>
                                </div>
                            </a>
                        </li>
                        <li class="divider"></li>
                        <li>
                            <div class="text-center link-block">
                                <a href="notifications.html">
                                    <strong>See All Alerts</strong>
                                    <i class="fa fa-angle-right"></i>
                                </a>
                            </div>
                        </li>
                    </ul>
                </li>


                <li>
                    <a href="login.html">
                        <i class="fa fa-sign-out"></i> Log out
                    </a>
                </li>
                <li>
                    <a class="right-sidebar-toggle">
                        <i class="fa fa-tasks"></i>
                    </a>
                </li>
            </ul>
            
        </nav>

        </div>
        <!-- <app-dashboard2 /> -->
        <!-- <app-dashboard3 /> -->
        <!-- <app-dashboard4 /> -->
        <!-- <app-dashboard5 /> -->
        <!-- <app-layout /> -->
        <!-- <app-metrics /> -->
        <!-- <app-widgets /> -->
        <!-- <app-grid /> -->
        <!-- <app-css /> -->
        <!-- <app-packages /> -->
        <!-- <app-flot_chart /> -->
        <!-- <app-morris /> -->
        <!-- <app-rickshaw /> -->
        <!-- <app-chartjs /> -->
        <!-- <app-chartlist /> -->
    <!-- <app-c3_chart /> -->
        <!-- <app-peity /> -->
        <!-- <app-sparkline /> -->
        <!-- <app-inbox /> -->
        <!-- <app-email-view /> -->
        <!-- <app-email-compose /> -->
        <!-- <app-email-templates /> -->
        <!-- <app-basic-form /> -->
        <!-- <app-form-advance /> -->
        <!-- <app-form-wazard /> -->
        <!-- <app-file-upload /> -->
        <!-- <app-text-editor /> -->
        <!-- <app-form-autocomplete /> -->
        <!-- <app-markdown /> -->
        <!-- <app-search-result /> -->
        <!-- <app-invoice /> -->
        <!-- <app-empty /> -->
        <!-- <app-statictable /> -->
        <!-- <app-datatable /> -->
        <!-- <app-footable /> -->
        <!-- <app-jqgrid /> -->
        <!-- <app-lightbox /> -->
        <!-- <app-slick /> -->
        <!-- <app-bootstrap /> -->
    <!-- <app-thirdlevel /> -->
    <!-- <app-orders /> -->
    <app-timeline />


        <app-footer />
</div>

</div>
</template>

<script>
// import dashboard1 from './dashboard1.vue'
// import dashboard2 from './dashboard2.vue'
// import dashboard3 from './dashboard3.vue'
// import dashboard4 from './dashboard4.vue'
// import dashboard5 from './dashboard5.vue'
// import layout from './layout.vue'
// import metrics from './metrics.vue'
// import widgets from './widgets.vue'
// import grid_option from './grid_option.vue'
// import css_animation from './css_animation.vue'
// import packages from './packages.vue'
// import flot_chart from './graphs/flot_chart.vue'
// import morris from './graphs/morris.vue'
// import rickshaw_chart from './graphs/rickshaw_chart.vue'
// import chartjs from './graphs/chartjs.vue'
// import chartlist from './graphs/chartlist.vue'
// import c3_chart from './graphs/c3_chart.vue'
// import peity from './graphs/peity.vue'
// import sparkline from  './graphs/sparkline.vue'
// import inbox from './mailbox/inbox.vue'
// import email_view from './mailbox/email_view.vue'
// import email_compose from './mailbox/email_compose.vue'
// import email_templates from './mailbox/email_templates.vue'
// import basic_form from './forms/basic_form.vue'
// import form_advance from './forms/form_advance.vue'
// import form_wazard from './forms/form_wazard.vue'
// import file_upload from './forms/file_upload.vue'
// import text_editor from './forms/text_editor.vue'
// import form_autocomplete from './forms/form_autocomplete.vue'
// import mark_down from './forms/mark_down.vue'
// import search_result from './other-pages/search_result.vue'
// import invoiceVue from './other-pages/invoice.vue'
// import emptyVue from './other-pages/empty.vue'
// import datatableVue from './tables/datatable.vue'
// import statictableVue from './tables/statictable.vue'
// import footableVue from './tables/footable.vue'
// import jqgridVue from './tables/jqgrid.vue'
// import lightboxVue from './gallery/lightbox.vue'
// import slickVue from './gallery/slick.vue'
// import bootstrap_carouselVue from './gallery/bootstrap_carousel.vue'
// import thirdlevel from './menulevel/thirdlevel.vue'
// import thirdlevel from './menulevel/thirdlevel.vue'
// import orders from './Ecommerce/orders.vue'
import timeline from './app-view/timeline.vue'



import footer from './footer.vue'



export default {
components:{
    // 'app-dashboard1':dashboard1,
    // 'app-dashboard2':dashboard2,
    // 'app-dashboard3':dashboard3,
    // 'app-dashboard4':dashboard4,
    // 'app-dashboard5':dashboard5,
    // 'app-layout':layout,
    // 'app-metrics':metrics,
    // 'app-widgets':widgets,
    // 'app-grid':grid_option,
    // 'app-css':css_animation,
    // 'app-packages' :packages,
    // 'app-flot_chart':flot_chart,
    // 'app-morris':morris,
    // 'app-rickshaw':rickshaw_chart,
    // 'app-chartjs':chartjs,
    // 'app-chartlist':chartlist,
    // 'app-c3_chart':c3_chart,
    // 'app-peity':peity,
    // 'app-sparkline':sparkline,
        // 'app-inbox':inbox,
        // 'app-email-view':email_view,
        // 'app-email-compose':email_compose,
        // 'app-email-templates':email_templates,
        // 'app-basic-form':basic_form,
        // 'app-form-advance':form_advance,
        // 'app-form-wazard':form_wazard,
        // 'app-file-upload':file_upload,
        // 'app-text-editor':text_editor,
        // 'app-form-autocomplete':form_autocomplete,
        // 'app-markdown':mark_down,
        // 'app-search-result':search_result,
        // 'app-invoice':invoiceVue,
        // 'app-empty':emptyVue,
        // 'app-statictable':statictableVue,
        // 'app-datatable':datatableVue,
        // 'app-footable':footableVue,
        // 'app-jqgrid':jqgridVue,
        // 'app-lightbox':lightboxVue,
        // 'app-slick':slickVue,
        // 'app-bootstrap':bootstrap_carouselVue,
        //  'app-thirdlevel':thirdlevel,
        // 'app-orders':orders,
        'app-timeline':timeline,


   'app-footer':footer

}
}
</script>

<style>

</style>