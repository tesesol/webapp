# webapp
<!DOCTYPE html>
<html xmlns:th="http://www.thymeleaf.org">

<head>
    <!-- 页面meta -->
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">


    <title>和正后台管理页面</title>
    <meta name="description" content="AdminLTE2定制版">
    <meta name="keywords" content="AdminLTE2定制版">

    <!-- Tell the browser to be responsive to screen width -->
    <meta content="width=device-width,initial-scale=1,maximum-scale=1,user-scalable=no" name="viewport">

    <!--[if lt IE 9]>
    <script src="/js/html5shiv.min.js"></script>
    <script src="/js/respond.min.js"></script>
    <![endif]-->


    <link rel="stylesheet" th:href="@{/webapp/plugins/bootstrap/css/bootstrap.min.css}">
    <link rel="stylesheet" th:href="@{/webapp/plugins/font-awesome/css/font-awesome.min.css}">
    <link rel="stylesheet" th:href="@{/webapp/plugins/ionicons/css/ionicons.min.css}">
    <link rel="stylesheet" th:href="@{/webapp/plugins/iCheck/square/blue.css}">
    <link rel="stylesheet" th:href="@{/webapp/plugins/morris/morris.css}">
    <link rel="stylesheet" th:href="@{/webapp/plugins/jvectormap/jquery-jvectormap-1.2.2.css}">
    <link rel="stylesheet" th:href="@{/webapp/plugins/datepicker/datepicker3.css}">
    <link rel="stylesheet" th:href="@{/webapp/plugins/daterangepicker/daterangepicker.css}">
    <link rel="stylesheet" th:href="@{/webapp/plugins/bootstrap-wysihtml5/bootstrap3-wysihtml5.min.css}">
    <link rel="stylesheet" th:href="@{/webapp/plugins/datatables/dataTables.bootstrap.css}">
    <link rel="stylesheet" th:href="@{/webapp/plugins/treeTable/jquery.treetable.css}">
    <link rel="stylesheet" th:href="@{/webapp/plugins/treeTable/jquery.treetable.theme.default.css}">
    <link rel="stylesheet" th:href="@{/webapp/plugins/select2/select2.css}">
    <link rel="stylesheet" th:href="@{/webapp/plugins/colorpicker/bootstrap-colorpicker.min.css}">
    <link rel="stylesheet" th:href="@{/webapp/plugins/bootstrap-markdown/css/bootstrap-markdown.min.css}">
    <link rel="stylesheet" th:href="@{/webapp/plugins/adminLTE/css/AdminLTE.css}">
    <link rel="stylesheet" th:href="@{/webapp/plugins/adminLTE/css/skins/_all-skins.min.css}">
    <link rel="stylesheet" th:href="@{/webapp/css/style.css}">
    <link rel="stylesheet" th:href="@{/webapp/plugins/ionslider/ion.rangeSlider.css}">
    <link rel="stylesheet" th:href="@{/webapp/plugins/ionslider/ion.rangeSlider.skinNice.css}">
    <link rel="stylesheet" th:href="@{/webapp/plugins/bootstrap-slider/slider.css}">
    <link rel="stylesheet" th:href="@{/webapp/plugins/bootstrap-datetimepicker/bootstrap-datetimepicker.css}">


</head>

<body class="hold-transition skin-purple sidebar-mini">

    <div class="wrapper" >
        <div class="content-wrapper" style="height: 800px;">
            <iframe marginwidth=0 marginheight=0 width="100%" height="100%" th:src="@{/time/index.html}" frameborder="no"></iframe>
        </div>
    </div>


<script th:src="@{/webapp/plugins/jQuery/jquery-2.2.3.min.js}"></script>
<script th:src="@{/webapp/plugins/jQueryUI/jquery-ui.min.js}"></script>
<script>
    $.widget.bridge('uibutton', $.ui.button);
</script>
<script th:src="@{/webapp/plugins/bootstrap/js/bootstrap.min.js}"></script>
<script th:src="@{/webapp/plugins/raphael/raphael-min.js}"></script>
<script th:src="@{/webapp/plugins/morris/morris.min.js}"></script>
<script th:src="@{/webapp/plugins/sparkline/jquery.sparkline.min.js}"></script>
<script th:src="@{/webapp/plugins/jvectormap/jquery-jvectormap-1.2.2.min.js}"></script>
<script th:src="@{/webapp/plugins/jvectormap/jquery-jvectormap-world-mill-en.js}"></script>
<script th:src="@{/webapp/plugins/knob/jquery.knob.js}"></script>
<script th:src="@{/webapp/plugins/daterangepicker/moment.min.js}"></script>
<script th:src="@{/webapp/plugins/daterangepicker/daterangepicker.js}"></script>
<script th:src="@{/webapp/plugins/daterangepicker/daterangepicker.zh-CN.js}"></script>
<script th:src="@{/webapp/plugins/datepicker/bootstrap-datepicker.js}"></script>
<script th:src="@{/webapp/plugins/datepicker/locales/bootstrap-datepicker.zh-CN.js}"></script>
<script th:src="@{/webapp/plugins/bootstrap-wysihtml5/bootstrap3-wysihtml5.all.min.js}"></script>
<script th:src="@{/webapp/plugins/slimScroll/jquery.slimscroll.min.js}"></script>
<script th:src="@{/webapp/plugins/fastclick/fastclick.js}"></script>
<script th:src="@{/webapp/plugins/iCheck/icheck.min.js}"></script>
<script th:src="@{/webapp/plugins/adminLTE/js/app.min.js}"></script>
<script th:src="@{/webapp/plugins/treeTable/jquery.treetable.js}"></script>
<script th:src="@{/webapp/plugins/select2/select2.full.min.js}"></script>
<script th:src="@{/webapp/plugins/colorpicker/bootstrap-colorpicker.min.js}"></script>
<script th:src="@{/webapp/plugins/input-mask/jquery.inputmask.js}"></script>
<script th:src="@{/webapp/plugins/input-mask/jquery.inputmask.date.extensions.js}"></script>
<script th:src="@{/webapp/plugins/input-mask/jquery.inputmask.extensions.js}"></script>
<script th:src="@{/webapp/plugins/datatables/jquery.dataTables.min.js}"></script>
<script th:src="@{/webapp/plugins/datatables/dataTables.bootstrap.min.js}"></script>
<script th:src="@{/webapp/plugins/chartjs/Chart.min.js}"></script>
<script th:src="@{/webapp/plugins/flot/jquery.flot.min.js}"></script>
<script th:src="@{/webapp/plugins/flot/jquery.flot.resize.min.js}"></script>
<script th:src="@{/webapp/plugins/flot/jquery.flot.pie.min.js}"></script>
<script th:src="@{/webapp/plugins/flot/jquery.flot.categories.min.js}"></script>
<script th:src="@{/webapp/plugins/ionslider/ion.rangeSlider.min.js}"></script>
<script th:src="@{/webapp/plugins/bootstrap-slider/bootstrap-slider.js}"></script>
<script th:src="@{/webapp/plugins/bootstrap-datetimepicker/bootstrap-datetimepicker.js}"></script>
<script th:src="@{/webapp/plugins/bootstrap-datetimepicker/locales/bootstrap-datetimepicker.zh-CN.js}"></script>
<script th:src="@{/hezheng/js/sweet.js}"></script>

</body>

</html>
