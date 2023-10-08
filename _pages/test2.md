---
layout: default2
permalink: /pages/dashboard-instructor.html
head: "head4.html"
stylesheets:
- url: "/assets/libs/bootstrap-select/dist/css/bootstrap-select.min.css"
- url: "/assets/fonts/feather/feather.css"
- url: "/assets/libs/bootstrap-icons/font/bootstrap-icons.css"
- url: "/assets/libs/@mdi/font/css/materialdesignicons.min.css"
- url: "/assets/libs/simplebar/dist/simplebar.min.css"
extrascripts:
- url: "/assets/libs/jquery/dist/jquery.min.js"
- url: "/assets/libs/bootstrap/dist/js/bootstrap.bundle.min.js"
- url: "/assets/libs/simplebar/dist/simplebar.min.js"
- url: "/assets/js/theme.min.js"
- url: "/assets/libs/apexcharts/dist/apexcharts.min.js"
- url: "/assets/js/vendors/chart.js"
myfooter:
- url: "footer1a.html"
---
<section class="pt-5 pb-5">
<div class="container">
<!-- User info -->
<div class="row align-items-center">
<div class="col-xl-12 col-lg-12 col-md-12 col-12">
<!-- Bg -->
<div class="pt-16 rounded-top" style="
background: url(/assets/images/background/profile-bg.jpg) no-repeat;
background-size: cover;
"></div>
<div class="card px-4 pt-2 pb-4 shadow-sm rounded-top-0 rounded-bottom-0 rounded-bottom-md-2 ">
<div class="d-flex align-items-end justify-content-between  ">
<div class="d-flex align-items-center">
<div
class="me-2 position-relative d-flex justify-content-end align-items-end mt-n5">
<img src="/assets/images/avatar/avatar-1.jpg"
class="avatar-xl rounded-circle border border-4 border-white position-relative"
alt="avatar">
<a href="#" class="position-absolute top-0 end-0" data-bs-toggle="tooltip"
data-placement="top" title="Verified">
<img src="/assets/images/svg/checked-mark.svg" alt="checked" height="30"
width="30">
</a>
</div>
<div class="lh-1">
<h2 class="mb-0">Jenny Wilson</h2>
<p class="mb-0 d-block">@Jennywilson</p>
</div>
</div>
<div>
<a href="add-course.html" class="btn btn-primary d-none d-md-block">Create New
Course</a>
</div>
</div>
</div>
</div>
</div>

<!-- Content -->

<div class="row mt-0 mt-md-4">
<div class="col-lg-3 col-md-4 col-12">
<!-- User profile -->
{% include sidenav1.html %}
</div>
<div class="col-lg-9 col-md-8 col-12">
<div class="row">
<div class="col-lg-4 col-md-12 col-12">
<!-- Card -->
{% include card1.html %}
</div>

<div class="col-lg-4 col-md-12 col-12">
<!-- Card -->
{% include card2.html %}
</div>
<div class="col-lg-4 col-md-12 col-12">
<!-- Card -->
{% include card3.html %}
</div>
<!-- Card -->
{% include card4.html %}
<!-- Card -->
<div class="card mb-4">
<!-- Card header -->
<div class="card-header">
<h3 class="h4 mb-0">Order</h3>
</div>
<!-- Card body -->
<div class="card-body">
<div id="orderColumn" class="apex-charts"></div>
</div>
</div>
<div class="card mb-4">
<!-- Card header -->
<div class="card-header">
<h3 class="h4 mb-0">Best Selling Courses</h3>
</div>
<!-- Table -->
<div class="table-responsive">
<table class="table mb-0 table-hover table-centered text-nowrap">
<!-- Table Head -->
<thead class="table-light">
<tr>
<th scope="col">COURSES</th>
<th scope="col">SALES</th>
<th scope="col">AMOUNT</th>
<th scope="col"></th>
</tr>
</thead>
<!-- Table Body -->
<tbody>
<tr>
<td>
<a href="#">
<div class="d-flex align-items-center">
<img src="/assets/images/course/course-laravel.jpg" alt="course"
class="rounded img-4by3-lg">
<h5 class="ms-3 text-primary-hover mb-0">
Building Scalable APIs with GraphQL
</h5>
</div>
</a>
</td>
<td>34</td>
<td>$3,145.23</td>
<td>
<span class="dropdown dropstart">
<a class="btn-icon btn btn-ghost btn-sm rounded-circle" href="#"
role="button" id="courseDropdown1" data-bs-toggle="dropdown"
data-bs-offset="-20,20" aria-expanded="false">
<i class="fe fe-more-vertical"></i>
</a>
<span class="dropdown-menu" aria-labelledby="courseDropdown1">
<span class="dropdown-header">Setting </span>
<a class="dropdown-item" href="#"><i
class="fe fe-edit dropdown-item-icon"></i>Edit</a>
<a class="dropdown-item" href="#"><i
class="fe fe-trash dropdown-item-icon"></i>Remove</a>
</span>
</span>
</td>
</tr>
<tr>
<td>
<a href="#">
<div class="d-flex align-items-center">
<img src="/assets/images/course/course-sass.jpg" alt="course"
class="rounded img-4by3-lg">
<h5 class="ms-3 text-primary-hover mb-0">
HTML5 Web Front End Development
</h5>
</div>
</a>
</td>
<td>30</td>
<td>$2,611.82</td>
<td>
<span class="dropdown dropstart">
<a class="btn-icon btn btn-ghost btn-sm rounded-circle" href="#"
role="button" id="courseDropdown2" data-bs-toggle="dropdown"
data-bs-offset="-20,20" aria-expanded="false">
<i class="fe fe-more-vertical"></i>
</a>
<span class="dropdown-menu" aria-labelledby="courseDropdown2">
<span class="dropdown-header">Setting </span>
<a class="dropdown-item" href="#"><i
class="fe fe-edit dropdown-item-icon"></i>Edit</a>
<a class="dropdown-item" href="#"><i
class="fe fe-trash dropdown-item-icon"></i>Remove</a>
</span>
</span>
</td>
</tr>
<tr>
<td>
<a href="#">
<div class="d-flex align-items-center">
<img src="/assets/images/course/course-vue.jpg" alt="course"
class="rounded img-4by3-lg">
<h5 class="ms-3 text-primary-hover mb-0">
Learn JavaScript Courses from Scratch
</h5>
</div>
</a>
</td>
<td>26</td>
<td>$2,372.19</td>
<td>
<span class="dropdown dropstart">
<a class="btn-icon btn btn-ghost btn-sm rounded-circle" href="#"
role="button" id="courseDropdown3" data-bs-toggle="dropdown"
data-bs-offset="-20,20" aria-expanded="false">
<i class="fe fe-more-vertical"></i>
</a>
<span class="dropdown-menu" aria-labelledby="courseDropdown3">
<span class="dropdown-header">Setting </span>
<a class="dropdown-item" href="#"><i
class="fe fe-edit dropdown-item-icon"></i>Edit</a>
<a class="dropdown-item" href="#"><i
class="fe fe-trash dropdown-item-icon"></i>Remove</a>
</span>
</span>
</td>
</tr>
<tr>
<td>
<a href="#">
<div class="d-flex align-items-center">
<img src="/assets/images/course/course-react.jpg" alt="course"
class="rounded img-4by3-lg">
<h5 class="ms-3 text-primary-hover mb-0">
Get Started: React Js Courses
</h5>
</div>
</a>
</td>
<td>20</td>
<td>$1,145.23</td>
<td>
<span class="dropdown dropstart">
<a class="btn-icon btn btn-ghost btn-sm rounded-circle" href="#"
role="button" id="courseDropdown4" data-bs-toggle="dropdown"
data-bs-offset="-20,20" aria-expanded="false">
<i class="fe fe-more-vertical"></i>
</a>
<span class="dropdown-menu" aria-labelledby="courseDropdown4">
<span class="dropdown-header">Setting </span>
<a class="dropdown-item" href="#"><i
class="fe fe-edit dropdown-item-icon"></i>Edit</a>
<a class="dropdown-item" href="#"><i
class="fe fe-trash dropdown-item-icon"></i>Remove</a>
</span>
</span>
</td>
</tr>
</tbody>
</table>
</div>
</div>
</div>
</div>
</div>
</section>