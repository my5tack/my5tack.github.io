---
layout: default1
permalink: /albums.html
title:  "Welcome to Emersa"
date:   2023-02-19 03:52:04 +0000
categories: album
---
<!-- Container START -->
<div class="container">
<div class="row g-4">

{% include sidenav.html %}

<!-- Main content START -->
<div class="col-md-8 col-lg-6 vstack gap-4">
<!-- Card START -->
<div class="card">
<!-- Card header START -->
<div class="card-header d-sm-flex text-center align-items-center justify-content-between border-0 pb-0">
<h1 class="card-title h4">Photos</h1>
<!-- Button modal -->
<a class="btn btn-primary-soft" href="#" data-bs-toggle="modal" data-bs-target="#modalCreateAlbum"> <i class="fa-solid fa-plus pe-1"></i> Create album</a>
</div>
<!-- Card header START -->
<!-- Card body START -->
<div class="card-body">

<!-- Tab nav line START -->
<ul class="nav nav-tabs nav-bottom-line justify-content-center justify-content-md-start">
<li class="nav-item"> <a class="nav-link active" data-bs-toggle="tab" href="#tab-1"> Photos of you </a> </li>
<li class="nav-item"> <a class="nav-link" data-bs-toggle="tab" href="#tab-2"> Your photos </a> </li>
<li class="nav-item"> <a class="nav-link" data-bs-toggle="tab" href="#tab-3"> Recently added </a> </li>
<li class="nav-item"> <a class="nav-link" data-bs-toggle="tab" href="#tab-4"> Family </a> </li>
<li class="nav-item"> <a class="nav-link" data-bs-toggle="tab" href="#tab-5"> Albums </a> </li>
</ul>
<!-- Tab nav line START -->

<!-- Album Tab content START -->
<div class="tab-content mb-0 pb-0">

<!-- Photos of you tab START -->
<div class="tab-pane fade show active" id="tab-1">
<div class="row g-3">

<!-- Add photo START -->
<div class="col-6 col-lg-3">
<div class="border border-2 border-dashed h-100 rounded text-center d-flex align-items-center justify-content-center position-relative">
<a class="stretched-link" href="#!">
<i class="fa-solid fa-camera-retro fs-1"></i>
<h6 class="mt-2">Add photo</h6>
</a>
</div>
</div>
<!-- Add photo END -->

<!-- Photo item START -->
<div class="col-6 col-lg-3 position-relative">
<div class="position-absolute bottom-0 end-0">
<!-- Dropdown START -->
<div class="dropdown mb-2 me-3">
<a href="#" class="icon-sm bg-primary text-white rounded-circle" id="photoActionEdit" data-bs-toggle="dropdown" aria-expanded="false">
<i class="bi bi-pencil-fill"></i>
</a>
<!-- Dropdown menu -->
<ul class="dropdown-menu dropdown-menu-end" aria-labelledby="photoActionEdit">
<li><a class="dropdown-item" href="#"> <i class="bi bi-tag fa-fw pe-1"></i> Remove Tag</a></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-download fa-fw pe-1"></i> Download </a></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-person fa-fw pe-1"></i> Make Profile Picture</a></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-person-bounding-box fa-fw pe-1"></i> Make Cover Photo</a></li>
<li><hr class="dropdown-divider"></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-flag fa-fw pe-1"></i> Report photo</a></li>
</ul>
</div>
</div>
<!-- Dropdown END -->
<a href="/assets/images/albums/01.jpg" data-gallery="image-popup" data-glightbox="description: .custom-desc2; descPosition: left;">
<img class="rounded img-fluid" src="/assets/images/albums/01.jpg" alt="">
</a>
<!-- glightbox Albums left bar START -->
<div class="glightbox-desc custom-desc2">
<div class="d-flex align-items-center justify-content-between">
<div class="d-flex align-items-center">
<!-- Avatar -->
<div class="avatar me-2">
<img class="avatar-img rounded-circle" src="/assets/images/avatar/04.jpg" alt="">
</div>
<!-- Info -->
<div>
<div class="nav nav-divider">
<h6 class="nav-item card-title mb-0">Lori Ferguson</h6>
<span class="nav-item small"> 2hr</span>
</div>
<p class="mb-0 small">Web Developer at Webestica</p>
</div>
</div>
<!-- Card feed action dropdown START -->
<div class="dropdown">
<a href="#" class="text-secondary btn btn-secondary-soft-hover py-1 px-2" id="cardFeedAction" data-bs-toggle="dropdown" aria-expanded="false">
<i class="bi bi-three-dots"></i>
</a>
<!-- Card feed action dropdown menu -->
<ul class="dropdown-menu dropdown-menu-end" aria-labelledby="cardFeedAction">
<li><a class="dropdown-item" href="#"> <i class="bi bi-bookmark fa-fw pe-2"></i>Save post</a></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-person-x fa-fw pe-2"></i>Unfollow lori ferguson </a></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-x-circle fa-fw pe-2"></i>Hide post</a></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-slash-circle fa-fw pe-2"></i>Block</a></li>
<li><hr class="dropdown-divider"></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-flag fa-fw pe-2"></i>Report post</a></li>
</ul>
</div>
<!-- Card feed action dropdown END -->
</div>
<p class="mt-3 mb-0">I'm so privileged to be involved in the @bootstrap hiring process! <a href="#">#internship #inclusivebusiness</a> <a href="#">#internship</a> <a href="#"> #hiring</a> <a href="#">#apply</a> </p>
<ul class="nav nav-stack py-3 small">
<li class="nav-item">
<a class="nav-link active" href="#!"> <i class="bi bi-hand-thumbs-up-fill pe-1"></i>Liked (56)</a>
</li>
<li class="nav-item">
<a class="nav-link" href="#!"> <i class="bi bi-chat-fill pe-1"></i>Comments (12)</a>
</li>
<!-- Card share action START -->
<li class="nav-item dropdown ms-auto">
<a class="nav-link mb-0" href="#" id="cardShareAction" data-bs-toggle="dropdown" aria-expanded="false">
<i class="bi bi-reply-fill fa-flip-horizontal pe-1"></i>Share (3)
</a>
<!-- Card share action dropdown menu -->
<ul class="dropdown-menu dropdown-menu-end" aria-labelledby="cardShareAction">
<li><a class="dropdown-item" href="#"> <i class="bi bi-envelope fa-fw pe-2"></i>Send via Direct Message</a></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-bookmark-check fa-fw pe-2"></i>Bookmark </a></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-link fa-fw pe-2"></i>Copy link to post</a></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-share fa-fw pe-2"></i>Share post via …</a></li>
<li><hr class="dropdown-divider"></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-pencil-square fa-fw pe-2"></i>Share to News Feed</a></li>
</ul>
</li>
<!-- Card share action END -->
</ul>
<!-- Add comment -->
<div class="d-flex mb-3">
<!-- Avatar -->
<div class="avatar avatar-xs me-2">
<img class="avatar-img rounded-circle" src="/assets/images/avatar/04.jpg" alt="">
</div>
<!-- Comment box  -->
<form class="position-relative w-100">
<textarea class="form-control pe-4 bg-light" rows="1" placeholder="Add a comment..."></textarea>
</form>
</div>
<!-- Comment wrap START -->
<ul class="comment-wrap list-unstyled ">
<!-- Comment item START -->
<li class="comment-item">
<div class="d-flex">
<!-- Avatar -->
<div class="avatar avatar-xs">
<img class="avatar-img rounded-circle" src="/assets/images/avatar/05.jpg" alt="">
</div>
<div class="ms-2">
<!-- Comment by -->
<div class="bg-light rounded-start-top-0 p-3 rounded">
<div class="d-flex justify-content-center">
<div class="me-2">
<h6 class="mb-1"> <a href="#!"> Frances Guerrero </a></h6>
<p class="small mb-0">Removed demands expense account in outward tedious do.</p>
</div>
<small>5hr</small>
</div>
</div>
<!-- Comment react -->
<ul class="nav nav-divider py-2 small">
<li class="nav-item">
<a class="nav-link" href="#!"> Like (3)</a>
</li>
<li class="nav-item">
<a class="nav-link" href="#!"> Reply</a>
</li>
<li class="nav-item">
<a class="nav-link" href="#!"> View 5 replies</a>
</li>
</ul>
</div>
</div>
</li>
</ul>
<!-- Comment wrap END -->
</div>
<!-- glightbox Albums left bar END  -->
</div>
<!-- Photo item END -->

<!-- Photo item START -->
<div class="col-6 col-lg-3 position-relative">
<div class="position-absolute bottom-0 end-0">
<!-- Dropdown START -->
<div class="dropdown mb-2 me-3">
<a href="#" class="icon-sm bg-primary text-white rounded-circle" id="photoActionEdit2" data-bs-toggle="dropdown" aria-expanded="false">
<i class="bi bi-pencil-fill"></i>
</a>
<!-- Dropdown menu -->
<ul class="dropdown-menu dropdown-menu-end" aria-labelledby="photoActionEdit2">
<li><a class="dropdown-item" href="#"> <i class="bi bi-tag fa-fw pe-1"></i> Remove Tag</a></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-download fa-fw pe-1"></i> Download </a></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-person fa-fw pe-1"></i> Make Profile Picture</a></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-person-bounding-box fa-fw pe-1"></i> Make Cover Photo</a></li>
<li><hr class="dropdown-divider"></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-flag fa-fw pe-1"></i> Report photo</a></li>
</ul>
</div>
</div>
<!-- Dropdown END -->
<a href="/assets/images/albums/02.jpg" data-gallery="image-popup" data-glightbox="description: .custom-desc2; descPosition: left;">
<img class="rounded img-fluid" src="/assets/images/albums/02.jpg" alt="">
</a>
<!-- glightbox Albums left bar START -->
<div class="glightbox-desc custom-desc2">
<div class="d-flex align-items-center justify-content-between">
<div class="d-flex align-items-center">
<!-- Avatar -->
<div class="avatar me-2">
<img class="avatar-img rounded-circle" src="/assets/images/avatar/04.jpg" alt="">
</div>
<!-- Info -->
<div>
<div class="nav nav-divider">
<h6 class="nav-item card-title mb-0">Lori Ferguson</h6>
<span class="nav-item small"> 2hr</span>
</div>
<p class="mb-0 small">Web Developer at Webestica</p>
</div>
</div>
<!-- Card feed action dropdown START -->
<div class="dropdown">
<a href="#" class="text-secondary btn btn-secondary-soft-hover py-1 px-2" id="cardFeedAction2" data-bs-toggle="dropdown" aria-expanded="false">
<i class="bi bi-three-dots"></i>
</a>
<!-- Card feed action dropdown menu -->
<ul class="dropdown-menu dropdown-menu-end" aria-labelledby="cardFeedAction2">
<li><a class="dropdown-item" href="#"> <i class="bi bi-bookmark fa-fw pe-2"></i>Save post</a></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-person-x fa-fw pe-2"></i>Unfollow lori ferguson </a></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-x-circle fa-fw pe-2"></i>Hide post</a></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-slash-circle fa-fw pe-2"></i>Block</a></li>
<li><hr class="dropdown-divider"></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-flag fa-fw pe-2"></i>Report post</a></li>
</ul>
</div>
<!-- Card feed action dropdown END -->
</div>
<p class="mt-3 mb-0">I'm so privileged to be involved in the @bootstrap hiring process! <a href="#">#internship #inclusivebusiness</a> <a href="#">#internship</a> <a href="#"> #hiring</a> <a href="#">#apply</a> </p>
<ul class="nav nav-stack py-3 small">
<li class="nav-item">
<a class="nav-link active" href="#!"> <i class="bi bi-hand-thumbs-up-fill pe-1"></i>Liked (56)</a>
</li>
<li class="nav-item">
<a class="nav-link" href="#!"> <i class="bi bi-chat-fill pe-1"></i>Comments (12)</a>
</li>
<!-- Card share action START -->
<li class="nav-item dropdown ms-auto">
<a class="nav-link mb-0" href="#" id="cardShareAction2" data-bs-toggle="dropdown" aria-expanded="false">
<i class="bi bi-reply-fill fa-flip-horizontal pe-1"></i>Share (3)
</a>
<!-- Card share action dropdown menu -->
<ul class="dropdown-menu dropdown-menu-end" aria-labelledby="cardShareAction2">
<li><a class="dropdown-item" href="#"> <i class="bi bi-envelope fa-fw pe-2"></i>Send via Direct Message</a></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-bookmark-check fa-fw pe-2"></i>Bookmark </a></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-link fa-fw pe-2"></i>Copy link to post</a></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-share fa-fw pe-2"></i>Share post via …</a></li>
<li><hr class="dropdown-divider"></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-pencil-square fa-fw pe-2"></i>Share to News Feed</a></li>
</ul>
</li>
<!-- Card share action END -->
</ul>
<!-- Add comment -->
<div class="d-flex mb-3">
<!-- Avatar -->
<div class="avatar avatar-xs me-2">
<img class="avatar-img rounded-circle" src="/assets/images/avatar/04.jpg" alt="">
</div>
<!-- Comment box  -->
<form class="position-relative w-100">
<textarea class="form-control pe-4 bg-light" rows="1" placeholder="Add a comment..."></textarea>
</form>
</div>
<!-- Comment wrap START -->
<ul class="comment-wrap list-unstyled ">
<!-- Comment item START -->
<li class="comment-item">
<div class="d-flex">
<!-- Avatar -->
<div class="avatar avatar-xs">
<img class="avatar-img rounded-circle" src="/assets/images/avatar/05.jpg" alt="">
</div>
<div class="ms-2">
<!-- Comment by -->
<div class="bg-light rounded-start-top-0 p-3 rounded">
<div class="d-flex justify-content-center">
<div class="me-2">
<h6 class="mb-1"> <a href="#!"> Frances Guerrero </a></h6>
<p class="small mb-0">Removed demands expense account in outward tedious do.</p>
</div>
<small>5hr</small>
</div>
</div>
<!-- Comment react -->
<ul class="nav nav-divider py-2 small">
<li class="nav-item">
<a class="nav-link" href="#!"> Like (3)</a>
</li>
<li class="nav-item">
<a class="nav-link" href="#!"> Reply</a>
</li>
<li class="nav-item">
<a class="nav-link" href="#!"> View 5 replies</a>
</li>
</ul>
</div>
</div>
</li>
</ul>
<!-- Comment wrap END -->
</div>
<!-- glightbox Albums left bar END  -->
</div>
<!-- Photo item END -->

<!-- Photo item START -->
<div class="col-6 col-lg-3 position-relative">
<div class="position-absolute bottom-0 end-0">
<!-- Dropdown START -->
<div class="dropdown mb-2 me-3">
<a href="#" class="icon-sm bg-primary text-white rounded-circle" id="photoActionEdit3" data-bs-toggle="dropdown" aria-expanded="false">
<i class="bi bi-pencil-fill"></i>
</a>
<!-- Dropdown menu -->
<ul class="dropdown-menu dropdown-menu-end" aria-labelledby="photoActionEdit3">
<li><a class="dropdown-item" href="#"> <i class="bi bi-tag fa-fw pe-1"></i> Remove Tag</a></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-download fa-fw pe-1"></i> Download </a></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-person fa-fw pe-1"></i> Make Profile Picture</a></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-person-bounding-box fa-fw pe-1"></i> Make Cover Photo</a></li>
<li><hr class="dropdown-divider"></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-flag fa-fw pe-1"></i> Report photo</a></li>
</ul>
</div>
</div>
<!-- Dropdown END -->
<a href="/assets/images/albums/03.jpg" data-gallery="image-popup" data-glightbox="description: .custom-desc2; descPosition: left;">
<img class="rounded img-fluid" src="/assets/images/albums/03.jpg" alt="">
</a>
<!-- glightbox Albums left bar START -->
<div class="glightbox-desc custom-desc2">
<div class="d-flex align-items-center justify-content-between">
<div class="d-flex align-items-center">
<!-- Avatar -->
<div class="avatar me-2">
<img class="avatar-img rounded-circle" src="/assets/images/avatar/04.jpg" alt="">
</div>
<!-- Info -->
<div>
<div class="nav nav-divider">
<h6 class="nav-item card-title mb-0">Lori Ferguson</h6>
<span class="nav-item small"> 2hr</span>
</div>
<p class="mb-0 small">Web Developer at Webestica</p>
</div>
</div>
<!-- Card feed action dropdown START -->
<div class="dropdown">
<a href="#" class="text-secondary btn btn-secondary-soft-hover py-1 px-2" id="cardFeedAction3" data-bs-toggle="dropdown" aria-expanded="false">
<i class="bi bi-three-dots"></i>
</a>
<!-- Card feed action dropdown menu -->
<ul class="dropdown-menu dropdown-menu-end" aria-labelledby="cardFeedAction3">
<li><a class="dropdown-item" href="#"> <i class="bi bi-bookmark fa-fw pe-2"></i>Save post</a></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-person-x fa-fw pe-2"></i>Unfollow lori ferguson </a></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-x-circle fa-fw pe-2"></i>Hide post</a></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-slash-circle fa-fw pe-2"></i>Block</a></li>
<li><hr class="dropdown-divider"></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-flag fa-fw pe-2"></i>Report post</a></li>
</ul>
</div>
<!-- Card feed action dropdown END -->
</div>
<p class="mt-3 mb-0">I'm so privileged to be involved in the @bootstrap hiring process! <a href="#">#internship #inclusivebusiness</a> <a href="#">#internship</a> <a href="#"> #hiring</a> <a href="#">#apply</a> </p>
<ul class="nav nav-stack py-3 small">
<li class="nav-item">
<a class="nav-link active" href="#!"> <i class="bi bi-hand-thumbs-up-fill pe-1"></i>Liked (56)</a>
</li>
<li class="nav-item">
<a class="nav-link" href="#!"> <i class="bi bi-chat-fill pe-1"></i>Comments (12)</a>
</li>
<!-- Card share action START -->
<li class="nav-item dropdown ms-auto">
<a class="nav-link mb-0" href="#" id="cardShareAction3" data-bs-toggle="dropdown" aria-expanded="false">
<i class="bi bi-reply-fill fa-flip-horizontal pe-1"></i>Share (3)
</a>
<!-- Card share action dropdown menu -->
<ul class="dropdown-menu dropdown-menu-end" aria-labelledby="cardShareAction3">
<li><a class="dropdown-item" href="#"> <i class="bi bi-envelope fa-fw pe-2"></i>Send via Direct Message</a></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-bookmark-check fa-fw pe-2"></i>Bookmark </a></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-link fa-fw pe-2"></i>Copy link to post</a></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-share fa-fw pe-2"></i>Share post via …</a></li>
<li><hr class="dropdown-divider"></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-pencil-square fa-fw pe-2"></i>Share to News Feed</a></li>
</ul>
</li>
<!-- Card share action END -->
</ul>
<!-- Add comment -->
<div class="d-flex mb-3">
<!-- Avatar -->
<div class="avatar avatar-xs me-2">
<img class="avatar-img rounded-circle" src="/assets/images/avatar/04.jpg" alt="">
</div>
<!-- Comment box  -->
<form class="position-relative w-100">
<textarea class="form-control pe-4 bg-light" rows="1" placeholder="Add a comment..."></textarea>
</form>
</div>
<!-- Comment wrap START -->
<ul class="comment-wrap list-unstyled ">
<!-- Comment item START -->
<li class="comment-item">
<div class="d-flex">
<!-- Avatar -->
<div class="avatar avatar-xs">
<img class="avatar-img rounded-circle" src="/assets/images/avatar/05.jpg" alt="">
</div>
<div class="ms-2">
<!-- Comment by -->
<div class="bg-light rounded-start-top-0 p-3 rounded">
<div class="d-flex justify-content-center">
<div class="me-2">
<h6 class="mb-1"> <a href="#!"> Frances Guerrero </a></h6>
<p class="small mb-0">Removed demands expense account in outward tedious do.</p>
</div>
<small>5hr</small>
</div>
</div>
<!-- Comment react -->
<ul class="nav nav-divider py-2 small">
<li class="nav-item">
<a class="nav-link" href="#!"> Like (3)</a>
</li>
<li class="nav-item">
<a class="nav-link" href="#!"> Reply</a>
</li>
<li class="nav-item">
<a class="nav-link" href="#!"> View 5 replies</a>
</li>
</ul>
</div>
</div>
</li>
</ul>
<!-- Comment wrap END -->
</div>
<!-- glightbox Albums left bar END  -->
</div>
<!-- Photo item END -->

<!-- Photo item START -->
<div class="col-6 col-lg-3 position-relative">
<div class="position-absolute bottom-0 end-0">
<!-- Dropdown START -->
<div class="dropdown mb-2 me-3">
<a href="#" class="icon-sm bg-primary text-white rounded-circle" id="photoActionEdit4" data-bs-toggle="dropdown" aria-expanded="false">
<i class="bi bi-pencil-fill"></i>
</a>
<!-- Dropdown menu -->
<ul class="dropdown-menu dropdown-menu-end" aria-labelledby="photoActionEdit4">
<li><a class="dropdown-item" href="#"> <i class="bi bi-tag fa-fw pe-1"></i> Remove Tag</a></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-download fa-fw pe-1"></i> Download </a></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-person fa-fw pe-1"></i> Make Profile Picture</a></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-person-bounding-box fa-fw pe-1"></i> Make Cover Photo</a></li>
<li><hr class="dropdown-divider"></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-flag fa-fw pe-1"></i> Report photo</a></li>
</ul>
</div>
</div>
<!-- Dropdown END -->
<a href="/assets/images/albums/04.jpg" data-gallery="image-popup" data-glightbox="description: .custom-desc2; descPosition: left;">
<img class="rounded img-fluid" src="/assets/images/albums/04.jpg" alt="">
</a>
<!-- glightbox Albums left bar START -->
<div class="glightbox-desc custom-desc2">
<div class="d-flex align-items-center justify-content-between">
<div class="d-flex align-items-center">
<!-- Avatar -->
<div class="avatar me-2">
<img class="avatar-img rounded-circle" src="/assets/images/avatar/04.jpg" alt="">
</div>
<!-- Info -->
<div>
<div class="nav nav-divider">
<h6 class="nav-item card-title mb-0">Lori Ferguson</h6>
<span class="nav-item small"> 2hr</span>
</div>
<p class="mb-0 small">Web Developer at Webestica</p>
</div>
</div>
<!-- Card feed action dropdown START -->
<div class="dropdown">
<a href="#" class="text-secondary btn btn-secondary-soft-hover py-1 px-2" id="cardFeedAction4" data-bs-toggle="dropdown" aria-expanded="false">
<i class="bi bi-three-dots"></i>
</a>
<!-- Card feed action dropdown menu -->
<ul class="dropdown-menu dropdown-menu-end" aria-labelledby="cardFeedAction4">
<li><a class="dropdown-item" href="#"> <i class="bi bi-bookmark fa-fw pe-2"></i>Save post</a></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-person-x fa-fw pe-2"></i>Unfollow lori ferguson </a></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-x-circle fa-fw pe-2"></i>Hide post</a></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-slash-circle fa-fw pe-2"></i>Block</a></li>
<li><hr class="dropdown-divider"></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-flag fa-fw pe-2"></i>Report post</a></li>
</ul>
</div>
<!-- Card feed action dropdown END -->
</div>
<p class="mt-3 mb-0">I'm so privileged to be involved in the @bootstrap hiring process! <a href="#">#internship #inclusivebusiness</a> <a href="#">#internship</a> <a href="#"> #hiring</a> <a href="#">#apply</a> </p>
<ul class="nav nav-stack py-3 small">
<li class="nav-item">
<a class="nav-link active" href="#!"> <i class="bi bi-hand-thumbs-up-fill pe-1"></i>Liked (56)</a>
</li>
<li class="nav-item">
<a class="nav-link" href="#!"> <i class="bi bi-chat-fill pe-1"></i>Comments (12)</a>
</li>
<!-- Card share action START -->
<li class="nav-item dropdown ms-auto">
<a class="nav-link mb-0" href="#" id="cardShareAction4" data-bs-toggle="dropdown" aria-expanded="false">
<i class="bi bi-reply-fill fa-flip-horizontal pe-1"></i>Share (3)
</a>
<!-- Card share action dropdown menu -->
<ul class="dropdown-menu dropdown-menu-end" aria-labelledby="cardShareAction4">
<li><a class="dropdown-item" href="#"> <i class="bi bi-envelope fa-fw pe-2"></i>Send via Direct Message</a></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-bookmark-check fa-fw pe-2"></i>Bookmark </a></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-link fa-fw pe-2"></i>Copy link to post</a></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-share fa-fw pe-2"></i>Share post via …</a></li>
<li><hr class="dropdown-divider"></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-pencil-square fa-fw pe-2"></i>Share to News Feed</a></li>
</ul>
</li>
<!-- Card share action END -->
</ul>
<!-- Add comment -->
<div class="d-flex mb-3">
<!-- Avatar -->
<div class="avatar avatar-xs me-2">
<img class="avatar-img rounded-circle" src="/assets/images/avatar/04.jpg" alt="">
</div>
<!-- Comment box  -->
<form class="position-relative w-100">
<textarea class="form-control pe-4 bg-light" rows="1" placeholder="Add a comment..."></textarea>
</form>
</div>
<!-- Comment wrap START -->
<ul class="comment-wrap list-unstyled ">
<!-- Comment item START -->
<li class="comment-item">
<div class="d-flex">
<!-- Avatar -->
<div class="avatar avatar-xs">
<img class="avatar-img rounded-circle" src="/assets/images/avatar/05.jpg" alt="">
</div>
<div class="ms-2">
<!-- Comment by -->
<div class="bg-light rounded-start-top-0 p-3 rounded">
<div class="d-flex justify-content-center">
<div class="me-2">
<h6 class="mb-1"> <a href="#!"> Frances Guerrero </a></h6>
<p class="small mb-0">Removed demands expense account in outward tedious do.</p>
</div>
<small>5hr</small>
</div>
</div>
<!-- Comment react -->
<ul class="nav nav-divider py-2 small">
<li class="nav-item">
<a class="nav-link" href="#!"> Like (3)</a>
</li>
<li class="nav-item">
<a class="nav-link" href="#!"> Reply</a>
</li>
<li class="nav-item">
<a class="nav-link" href="#!"> View 5 replies</a>
</li>
</ul>
</div>
</div>
</li>
</ul>
<!-- Comment wrap END -->
</div>
<!-- glightbox Albums left bar END  -->
</div>
<!-- Photo item END -->

<!-- Photo item START -->
<div class="col-6 col-lg-3 position-relative">
<div class="position-absolute bottom-0 end-0">
<!-- Dropdown START -->
<div class="dropdown mb-2 me-3">
<a href="#" class="icon-sm bg-primary text-white rounded-circle" id="photoActionEdit5" data-bs-toggle="dropdown" aria-expanded="false">
<i class="bi bi-pencil-fill"></i>
</a>
<!-- Dropdown menu -->
<ul class="dropdown-menu dropdown-menu-end" aria-labelledby="photoActionEdit5">
<li><a class="dropdown-item" href="#"> <i class="bi bi-tag fa-fw pe-1"></i> Remove Tag</a></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-download fa-fw pe-1"></i> Download </a></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-person fa-fw pe-1"></i> Make Profile Picture</a></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-person-bounding-box fa-fw pe-1"></i> Make Cover Photo</a></li>
<li><hr class="dropdown-divider"></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-flag fa-fw pe-1"></i> Report photo</a></li>
</ul>
</div>
</div>
<!-- Dropdown END -->
<a href="/assets/images/albums/05.jpg" data-gallery="image-popup" data-glightbox="description: .custom-desc2; descPosition: left;">
<img class="rounded img-fluid" src="/assets/images/albums/05.jpg" alt="">
</a>
<!-- glightbox Albums left bar START -->
<div class="glightbox-desc custom-desc2">
<div class="d-flex align-items-center justify-content-between">
<div class="d-flex align-items-center">
<!-- Avatar -->
<div class="avatar me-2">
<img class="avatar-img rounded-circle" src="/assets/images/avatar/04.jpg" alt="">
</div>
<!-- Info -->
<div>
<div class="nav nav-divider">
<h6 class="nav-item card-title mb-0">Lori Ferguson</h6>
<span class="nav-item small"> 2hr</span>
</div>
<p class="mb-0 small">Web Developer at Webestica</p>
</div>
</div>
<!-- Card feed action dropdown START -->
<div class="dropdown">
<a href="#" class="text-secondary btn btn-secondary-soft-hover py-1 px-2" id="cardFeedAction5" data-bs-toggle="dropdown" aria-expanded="false">
<i class="bi bi-three-dots"></i>
</a>
<!-- Card feed action dropdown menu -->
<ul class="dropdown-menu dropdown-menu-end" aria-labelledby="cardFeedAction5">
<li><a class="dropdown-item" href="#"> <i class="bi bi-bookmark fa-fw pe-2"></i>Save post</a></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-person-x fa-fw pe-2"></i>Unfollow lori ferguson </a></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-x-circle fa-fw pe-2"></i>Hide post</a></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-slash-circle fa-fw pe-2"></i>Block</a></li>
<li><hr class="dropdown-divider"></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-flag fa-fw pe-2"></i>Report post</a></li>
</ul>
</div>
<!-- Card feed action dropdown END -->
</div>
<p class="mt-3 mb-0">I'm so privileged to be involved in the @bootstrap hiring process! <a href="#">#internship #inclusivebusiness</a> <a href="#">#internship</a> <a href="#"> #hiring</a> <a href="#">#apply</a> </p>
<ul class="nav nav-stack py-3 small">
<li class="nav-item">
<a class="nav-link active" href="#!"> <i class="bi bi-hand-thumbs-up-fill pe-1"></i>Liked (56)</a>
</li>
<li class="nav-item">
<a class="nav-link" href="#!"> <i class="bi bi-chat-fill pe-1"></i>Comments (12)</a>
</li>
<!-- Card share action START -->
<li class="nav-item dropdown ms-auto">
<a class="nav-link mb-0" href="#" id="cardShareAction5" data-bs-toggle="dropdown" aria-expanded="false">
<i class="bi bi-reply-fill fa-flip-horizontal pe-1"></i>Share (3)
</a>
<!-- Card share action dropdown menu -->
<ul class="dropdown-menu dropdown-menu-end" aria-labelledby="cardShareAction5">
<li><a class="dropdown-item" href="#"> <i class="bi bi-envelope fa-fw pe-2"></i>Send via Direct Message</a></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-bookmark-check fa-fw pe-2"></i>Bookmark </a></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-link fa-fw pe-2"></i>Copy link to post</a></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-share fa-fw pe-2"></i>Share post via …</a></li>
<li><hr class="dropdown-divider"></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-pencil-square fa-fw pe-2"></i>Share to News Feed</a></li>
</ul>
</li>
<!-- Card share action END -->
</ul>
<!-- Add comment -->
<div class="d-flex mb-3">
<!-- Avatar -->
<div class="avatar avatar-xs me-2">
<img class="avatar-img rounded-circle" src="/assets/images/avatar/04.jpg" alt="">
</div>
<!-- Comment box  -->
<form class="position-relative w-100">
<textarea class="form-control pe-4 bg-light" rows="1" placeholder="Add a comment..."></textarea>
</form>
</div>
<!-- Comment wrap START -->
<ul class="comment-wrap list-unstyled ">
<!-- Comment item START -->
<li class="comment-item">
<div class="d-flex">
<!-- Avatar -->
<div class="avatar avatar-xs">
<img class="avatar-img rounded-circle" src="/assets/images/avatar/05.jpg" alt="">
</div>
<div class="ms-2">
<!-- Comment by -->
<div class="bg-light rounded-start-top-0 p-3 rounded">
<div class="d-flex justify-content-center">
<div class="me-2">
<h6 class="mb-1"> <a href="#!"> Frances Guerrero </a></h6>
<p class="small mb-0">Removed demands expense account in outward tedious do.</p>
</div>
<small>5hr</small>
</div>
</div>
<!-- Comment react -->
<ul class="nav nav-divider py-2 small">
<li class="nav-item">
<a class="nav-link" href="#!"> Like (3)</a>
</li>
<li class="nav-item">
<a class="nav-link" href="#!"> Reply</a>
</li>
<li class="nav-item">
<a class="nav-link" href="#!"> View 5 replies</a>
</li>
</ul>
</div>
</div>
</li>
</ul>
<!-- Comment wrap END -->
</div>
<!-- glightbox Albums left bar END  -->
</div>
<!-- Photo item END -->

<!-- Photo item START -->
<div class="col-6 col-lg-3 position-relative">
<div class="position-absolute bottom-0 end-0">
<!-- Dropdown START -->
<div class="dropdown mb-2 me-3">
<a href="#" class="icon-sm bg-primary text-white rounded-circle" id="photoActionEdit6" data-bs-toggle="dropdown" aria-expanded="false">
<i class="bi bi-pencil-fill"></i>
</a>
<!-- Dropdown menu -->
<ul class="dropdown-menu dropdown-menu-end" aria-labelledby="photoActionEdit6">
<li><a class="dropdown-item" href="#"> <i class="bi bi-tag fa-fw pe-1"></i> Remove Tag</a></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-download fa-fw pe-1"></i> Download </a></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-person fa-fw pe-1"></i> Make Profile Picture</a></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-person-bounding-box fa-fw pe-1"></i> Make Cover Photo</a></li>
<li><hr class="dropdown-divider"></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-flag fa-fw pe-1"></i> Report photo</a></li>
</ul>
</div>
</div>
<!-- Dropdown END -->
<a href="/assets/images/albums/06.jpg" data-gallery="image-popup" data-glightbox="description: .custom-desc2; descPosition: left;">
<img class="rounded img-fluid" src="/assets/images/albums/06.jpg" alt="">
</a>
<!-- glightbox Albums left bar START -->
<div class="glightbox-desc custom-desc2">
<div class="d-flex align-items-center justify-content-between">
<div class="d-flex align-items-center">
<!-- Avatar -->
<div class="avatar me-2">
<img class="avatar-img rounded-circle" src="/assets/images/avatar/04.jpg" alt="">
</div>
<!-- Info -->
<div>
<div class="nav nav-divider">
<h6 class="nav-item card-title mb-0">Lori Ferguson</h6>
<span class="nav-item small"> 2hr</span>
</div>
<p class="mb-0 small">Web Developer at Webestica</p>
</div>
</div>
<!-- Card feed action dropdown START -->
<div class="dropdown">
<a href="#" class="text-secondary btn btn-secondary-soft-hover py-1 px-2" id="cardFeedAction6" data-bs-toggle="dropdown" aria-expanded="false">
<i class="bi bi-three-dots"></i>
</a>
<!-- Card feed action dropdown menu -->
<ul class="dropdown-menu dropdown-menu-end" aria-labelledby="cardFeedAction6">
<li><a class="dropdown-item" href="#"> <i class="bi bi-bookmark fa-fw pe-2"></i>Save post</a></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-person-x fa-fw pe-2"></i>Unfollow lori ferguson </a></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-x-circle fa-fw pe-2"></i>Hide post</a></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-slash-circle fa-fw pe-2"></i>Block</a></li>
<li><hr class="dropdown-divider"></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-flag fa-fw pe-2"></i>Report post</a></li>
</ul>
</div>
<!-- Card feed action dropdown END -->
</div>
<p class="mt-3 mb-0">I'm so privileged to be involved in the @bootstrap hiring process! <a href="#">#internship #inclusivebusiness</a> <a href="#">#internship</a> <a href="#"> #hiring</a> <a href="#">#apply</a> </p>
<ul class="nav nav-stack py-3 small">
<li class="nav-item">
<a class="nav-link active" href="#!"> <i class="bi bi-hand-thumbs-up-fill pe-1"></i>Liked (56)</a>
</li>
<li class="nav-item">
<a class="nav-link" href="#!"> <i class="bi bi-chat-fill pe-1"></i>Comments (12)</a>
</li>
<!-- Card share action START -->
<li class="nav-item dropdown ms-auto">
<a class="nav-link mb-0" href="#" id="cardShareAction6" data-bs-toggle="dropdown" aria-expanded="false">
<i class="bi bi-reply-fill fa-flip-horizontal pe-1"></i>Share (3)
</a>
<!-- Card share action dropdown menu -->
<ul class="dropdown-menu dropdown-menu-end" aria-labelledby="cardShareAction6">
<li><a class="dropdown-item" href="#"> <i class="bi bi-envelope fa-fw pe-2"></i>Send via Direct Message</a></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-bookmark-check fa-fw pe-2"></i>Bookmark </a></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-link fa-fw pe-2"></i>Copy link to post</a></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-share fa-fw pe-2"></i>Share post via …</a></li>
<li><hr class="dropdown-divider"></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-pencil-square fa-fw pe-2"></i>Share to News Feed</a></li>
</ul>
</li>
<!-- Card share action END -->
</ul>
<!-- Add comment -->
<div class="d-flex mb-3">
<!-- Avatar -->
<div class="avatar avatar-xs me-2">
<img class="avatar-img rounded-circle" src="/assets/images/avatar/04.jpg" alt="">
</div>
<!-- Comment box  -->
<form class="position-relative w-100">
<textarea class="form-control pe-4 bg-light" rows="1" placeholder="Add a comment..."></textarea>
</form>
</div>
<!-- Comment wrap START -->
<ul class="comment-wrap list-unstyled ">
<!-- Comment item START -->
<li class="comment-item">
<div class="d-flex">
<!-- Avatar -->
<div class="avatar avatar-xs">
<img class="avatar-img rounded-circle" src="/assets/images/avatar/05.jpg" alt="">
</div>
<div class="ms-2">
<!-- Comment by -->
<div class="bg-light rounded-start-top-0 p-3 rounded">
<div class="d-flex justify-content-center">
<div class="me-2">
<h6 class="mb-1"> <a href="#!"> Frances Guerrero </a></h6>
<p class="small mb-0">Removed demands expense account in outward tedious do.</p>
</div>
<small>5hr</small>
</div>
</div>
<!-- Comment react -->
<ul class="nav nav-divider py-2 small">
<li class="nav-item">
<a class="nav-link" href="#!"> Like (3)</a>
</li>
<li class="nav-item">
<a class="nav-link" href="#!"> Reply</a>
</li>
<li class="nav-item">
<a class="nav-link" href="#!"> View 5 replies</a>
</li>
</ul>
</div>
</div>
</li>
</ul>
<!-- Comment wrap END -->
</div>
<!-- glightbox Albums left bar END  -->
</div>
<!-- Photo item END -->
</div>
</div>
<!-- Photos of you tab END -->

<!-- Your photos tab START -->
<div class="tab-pane fade" id="tab-2">
<div class="row g-3">

<!-- Add photo START -->
<div class="col-6 col-lg-3">
<div class="border border-2 border-dashed h-100 rounded text-center d-flex align-items-center justify-content-center position-relative">
<a class="stretched-link" href="#!">
<i class="fa-solid fa-camera-retro fs-1"></i>
<h6 class="mt-2">Add photo</h6>
</a>
</div>
</div>
<!-- Add photo END -->

<!-- Photo item START -->
<div class="col-6 col-lg-3 position-relative">
<div class="position-absolute bottom-0 end-0">
<!-- Dropdown START -->
<div class="dropdown mb-2 me-3">
<a href="#" class="icon-sm bg-primary text-white rounded-circle" id="photoActionEdit7" data-bs-toggle="dropdown" aria-expanded="false">
<i class="bi bi-pencil-fill"></i>
</a>
<!-- Dropdown menu -->
<ul class="dropdown-menu dropdown-menu-end" aria-labelledby="photoActionEdit7">
<li><a class="dropdown-item" href="#"> <i class="bi bi-tag fa-fw pe-1"></i> Remove Tag</a></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-download fa-fw pe-1"></i> Download </a></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-person fa-fw pe-1"></i> Make Profile Picture</a></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-person-bounding-box fa-fw pe-1"></i> Make Cover Photo</a></li>
<li><hr class="dropdown-divider"></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-flag fa-fw pe-1"></i> Report photo</a></li>
</ul>
</div>
</div>
<!-- Dropdown END -->
<a href="/assets/images/albums/01.jpg" data-gallery="image-popup" data-glightbox="description: .custom-desc2; descPosition: left;">
<img class="rounded img-fluid" src="/assets/images/albums/01.jpg" alt="">
</a>
<!-- glightbox Albums left bar START -->
<div class="glightbox-desc custom-desc2">
<div class="d-flex align-items-center justify-content-between">
<div class="d-flex align-items-center">
<!-- Avatar -->
<div class="avatar me-2">
<img class="avatar-img rounded-circle" src="/assets/images/avatar/04.jpg" alt="">
</div>
<!-- Info -->
<div>
<div class="nav nav-divider">
<h6 class="nav-item card-title mb-0">Lori Ferguson</h6>
<span class="nav-item small"> 2hr</span>
</div>
<p class="mb-0 small">Web Developer at Webestica</p>
</div>
</div>
<!-- Card feed action dropdown START -->
<div class="dropdown">
<a href="#" class="text-secondary btn btn-secondary-soft-hover py-1 px-2" id="cardFeedAction7" data-bs-toggle="dropdown" aria-expanded="false">
<i class="bi bi-three-dots"></i>
</a>
<!-- Card feed action dropdown menu -->
<ul class="dropdown-menu dropdown-menu-end" aria-labelledby="cardFeedAction7">
<li><a class="dropdown-item" href="#"> <i class="bi bi-bookmark fa-fw pe-2"></i>Save post</a></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-person-x fa-fw pe-2"></i>Unfollow lori ferguson </a></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-x-circle fa-fw pe-2"></i>Hide post</a></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-slash-circle fa-fw pe-2"></i>Block</a></li>
<li><hr class="dropdown-divider"></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-flag fa-fw pe-2"></i>Report post</a></li>
</ul>
</div>
<!-- Card feed action dropdown END -->
</div>
<p class="mt-3 mb-0">I'm so privileged to be involved in the @bootstrap hiring process! <a href="#">#internship #inclusivebusiness</a> <a href="#">#internship</a> <a href="#"> #hiring</a> <a href="#">#apply</a> </p>
<ul class="nav nav-stack py-3 small">
<li class="nav-item">
<a class="nav-link active" href="#!"> <i class="bi bi-hand-thumbs-up-fill pe-1"></i>Liked (56)</a>
</li>
<li class="nav-item">
<a class="nav-link" href="#!"> <i class="bi bi-chat-fill pe-1"></i>Comments (12)</a>
</li>
<!-- Card share action START -->
<li class="nav-item dropdown ms-auto">
<a class="nav-link mb-0" href="#" id="cardShareAction7" data-bs-toggle="dropdown" aria-expanded="false">
<i class="bi bi-reply-fill fa-flip-horizontal pe-1"></i>Share (3)
</a>
<!-- Card share action dropdown menu -->
<ul class="dropdown-menu dropdown-menu-end" aria-labelledby="cardShareAction7">
<li><a class="dropdown-item" href="#"> <i class="bi bi-envelope fa-fw pe-2"></i>Send via Direct Message</a></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-bookmark-check fa-fw pe-2"></i>Bookmark </a></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-link fa-fw pe-2"></i>Copy link to post</a></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-share fa-fw pe-2"></i>Share post via …</a></li>
<li><hr class="dropdown-divider"></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-pencil-square fa-fw pe-2"></i>Share to News Feed</a></li>
</ul>
</li>
<!-- Card share action END -->
</ul>
<!-- Add comment -->
<div class="d-flex mb-3">
<!-- Avatar -->
<div class="avatar avatar-xs me-2">
<img class="avatar-img rounded-circle" src="/assets/images/avatar/04.jpg" alt="">
</div>
<!-- Comment box  -->
<form class="position-relative w-100">
<textarea class="form-control pe-4 bg-light" rows="1" placeholder="Add a comment..."></textarea>
</form>
</div>
<!-- Comment wrap START -->
<ul class="comment-wrap list-unstyled ">
<!-- Comment item START -->
<li class="comment-item">
<div class="d-flex">
<!-- Avatar -->
<div class="avatar avatar-xs">
<img class="avatar-img rounded-circle" src="/assets/images/avatar/05.jpg" alt="">
</div>
<div class="ms-2">
<!-- Comment by -->
<div class="bg-light rounded-start-top-0 p-3 rounded">
<div class="d-flex justify-content-center">
<div class="me-2">
<h6 class="mb-1"> <a href="#!"> Frances Guerrero </a></h6>
<p class="small mb-0">Removed demands expense account in outward tedious do.</p>
</div>
<small>5hr</small>
</div>
</div>
<!-- Comment react -->
<ul class="nav nav-divider py-2 small">
<li class="nav-item">
<a class="nav-link" href="#!"> Like (3)</a>
</li>
<li class="nav-item">
<a class="nav-link" href="#!"> Reply</a>
</li>
<li class="nav-item">
<a class="nav-link" href="#!"> View 5 replies</a>
</li>
</ul>
</div>
</div>
</li>
</ul>
<!-- Comment wrap END -->
</div>
<!-- glightbox Albums left bar END  -->
</div>
<!-- Photo item END -->

<!-- Photo item START -->
<div class="col-6 col-lg-3 position-relative">
<div class="position-absolute bottom-0 end-0">
<!-- Dropdown START -->
<div class="dropdown mb-2 me-3">
<a href="#" class="icon-sm bg-primary text-white rounded-circle" id="postActionEdit2" data-bs-toggle="dropdown" aria-expanded="false">
<i class="bi bi-pencil-fill"></i>
</a>
<!-- Dropdown menu -->
<ul class="dropdown-menu dropdown-menu-end" aria-labelledby="postActionEdit2">
<li><a class="dropdown-item" href="#"> <i class="bi bi-tag fa-fw pe-1"></i> Remove Tag</a></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-download fa-fw pe-1"></i> Download </a></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-person fa-fw pe-1"></i> Make Profile Picture</a></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-person-bounding-box fa-fw pe-1"></i> Make Cover Photo</a></li>
<li><hr class="dropdown-divider"></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-flag fa-fw pe-1"></i> Report photo</a></li>
</ul>
</div>
</div>
<!-- Dropdown END -->
<a href="/assets/images/albums/02.jpg" data-gallery="image-popup" data-glightbox="description: .custom-desc2; descPosition: left;">
<img class="rounded img-fluid" src="/assets/images/albums/02.jpg" alt="">
</a>
<!-- glightbox Albums left bar START -->
<div class="glightbox-desc custom-desc2">
<div class="d-flex align-items-center justify-content-between">
<div class="d-flex align-items-center">
<!-- Avatar -->
<div class="avatar me-2">
<img class="avatar-img rounded-circle" src="/assets/images/avatar/04.jpg" alt="">
</div>
<!-- Info -->
<div>
<div class="nav nav-divider">
<h6 class="nav-item card-title mb-0">Lori Ferguson</h6>
<span class="nav-item small"> 2hr</span>
</div>
<p class="mb-0 small">Web Developer at Webestica</p>
</div>
</div>
<!-- Card feed action dropdown START -->
<div class="dropdown">
<a href="#" class="text-secondary btn btn-secondary-soft-hover py-1 px-2" id="cardFeedAction8" data-bs-toggle="dropdown" aria-expanded="false">
<i class="bi bi-three-dots"></i>
</a>
<!-- Card feed action dropdown menu -->
<ul class="dropdown-menu dropdown-menu-end" aria-labelledby="cardFeedAction8">
<li><a class="dropdown-item" href="#"> <i class="bi bi-bookmark fa-fw pe-2"></i>Save post</a></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-person-x fa-fw pe-2"></i>Unfollow lori ferguson </a></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-x-circle fa-fw pe-2"></i>Hide post</a></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-slash-circle fa-fw pe-2"></i>Block</a></li>
<li><hr class="dropdown-divider"></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-flag fa-fw pe-2"></i>Report post</a></li>
</ul>
</div>
<!-- Card feed action dropdown END -->
</div>
<p class="mt-3 mb-0">I'm so privileged to be involved in the @bootstrap hiring process! <a href="#">#internship #inclusivebusiness</a> <a href="#">#internship</a> <a href="#"> #hiring</a> <a href="#">#apply</a> </p>
<ul class="nav nav-stack py-3 small">
<li class="nav-item">
<a class="nav-link active" href="#!"> <i class="bi bi-hand-thumbs-up-fill pe-1"></i>Liked (56)</a>
</li>
<li class="nav-item">
<a class="nav-link" href="#!"> <i class="bi bi-chat-fill pe-1"></i>Comments (12)</a>
</li>
<!-- Card share action START -->
<li class="nav-item dropdown ms-auto">
<a class="nav-link mb-0" href="#" id="cardShareAction8" data-bs-toggle="dropdown" aria-expanded="false">
<i class="bi bi-reply-fill fa-flip-horizontal pe-1"></i>Share (3)
</a>
<!-- Card share action dropdown menu -->
<ul class="dropdown-menu dropdown-menu-end" aria-labelledby="cardShareAction8">
<li><a class="dropdown-item" href="#"> <i class="bi bi-envelope fa-fw pe-2"></i>Send via Direct Message</a></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-bookmark-check fa-fw pe-2"></i>Bookmark </a></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-link fa-fw pe-2"></i>Copy link to post</a></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-share fa-fw pe-2"></i>Share post via …</a></li>
<li><hr class="dropdown-divider"></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-pencil-square fa-fw pe-2"></i>Share to News Feed</a></li>
</ul>
</li>
<!-- Card share action END -->
</ul>
<!-- Add comment -->
<div class="d-flex mb-3">
<!-- Avatar -->
<div class="avatar avatar-xs me-2">
<img class="avatar-img rounded-circle" src="/assets/images/avatar/04.jpg" alt="">
</div>
<!-- Comment box  -->
<form class="position-relative w-100">
<textarea class="form-control pe-4 bg-light" rows="1" placeholder="Add a comment..."></textarea>
</form>
</div>
<!-- Comment wrap START -->
<ul class="comment-wrap list-unstyled ">
<!-- Comment item START -->
<li class="comment-item">
<div class="d-flex">
<!-- Avatar -->
<div class="avatar avatar-xs">
<img class="avatar-img rounded-circle" src="/assets/images/avatar/05.jpg" alt="">
</div>
<div class="ms-2">
<!-- Comment by -->
<div class="bg-light rounded-start-top-0 p-3 rounded">
<div class="d-flex justify-content-center">
<div class="me-2">
<h6 class="mb-1"> <a href="#!"> Frances Guerrero </a></h6>
<p class="small mb-0">Removed demands expense account in outward tedious do.</p>
</div>
<small>5hr</small>
</div>
</div>
<!-- Comment react -->
<ul class="nav nav-divider py-2 small">
<li class="nav-item">
<a class="nav-link" href="#!"> Like (3)</a>
</li>
<li class="nav-item">
<a class="nav-link" href="#!"> Reply</a>
</li>
<li class="nav-item">
<a class="nav-link" href="#!"> View 5 replies</a>
</li>
</ul>
</div>
</div>
</li>
</ul>
<!-- Comment wrap END -->
</div>
<!-- glightbox Albums left bar END  -->
</div>
<!-- Photo item END -->

<!-- Photo item START -->
<div class="col-6 col-lg-3 position-relative">
<div class="position-absolute bottom-0 end-0">
<!-- Dropdown START -->
<div class="dropdown mb-2 me-3">
<a href="#" class="icon-sm bg-primary text-white rounded-circle" id="photoActionEdit8" data-bs-toggle="dropdown" aria-expanded="false">
<i class="bi bi-pencil-fill"></i>
</a>
<!-- Dropdown menu -->
<ul class="dropdown-menu dropdown-menu-end" aria-labelledby="photoActionEdit8">
<li><a class="dropdown-item" href="#"> <i class="bi bi-tag fa-fw pe-1"></i> Remove Tag</a></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-download fa-fw pe-1"></i> Download </a></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-person fa-fw pe-1"></i> Make Profile Picture</a></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-person-bounding-box fa-fw pe-1"></i> Make Cover Photo</a></li>
<li><hr class="dropdown-divider"></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-flag fa-fw pe-1"></i> Report photo</a></li>
</ul>
</div>
</div>
<!-- Dropdown END -->
<a href="/assets/images/albums/03.jpg" data-gallery="image-popup" data-glightbox="description: .custom-desc2; descPosition: left;">
<img class="rounded img-fluid" src="/assets/images/albums/03.jpg" alt="">
</a>
<!-- glightbox Albums left bar START -->
<div class="glightbox-desc custom-desc2">
<div class="d-flex align-items-center justify-content-between">
<div class="d-flex align-items-center">
<!-- Avatar -->
<div class="avatar me-2">
<img class="avatar-img rounded-circle" src="/assets/images/avatar/04.jpg" alt="">
</div>
<!-- Info -->
<div>
<div class="nav nav-divider">
<h6 class="nav-item card-title mb-0">Lori Ferguson</h6>
<span class="nav-item small"> 2hr</span>
</div>
<p class="mb-0 small">Web Developer at Webestica</p>
</div>
</div>
<!-- Card feed action dropdown START -->
<div class="dropdown">
<a href="#" class="text-secondary btn btn-secondary-soft-hover py-1 px-2" id="cardFeedAction9" data-bs-toggle="dropdown" aria-expanded="false">
<i class="bi bi-three-dots"></i>
</a>
<!-- Card feed action dropdown menu -->
<ul class="dropdown-menu dropdown-menu-end" aria-labelledby="cardFeedAction9">
<li><a class="dropdown-item" href="#"> <i class="bi bi-bookmark fa-fw pe-2"></i>Save post</a></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-person-x fa-fw pe-2"></i>Unfollow lori ferguson </a></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-x-circle fa-fw pe-2"></i>Hide post</a></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-slash-circle fa-fw pe-2"></i>Block</a></li>
<li><hr class="dropdown-divider"></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-flag fa-fw pe-2"></i>Report post</a></li>
</ul>
</div>
<!-- Card feed action dropdown END -->
</div>
<p class="mt-3 mb-0">I'm so privileged to be involved in the @bootstrap hiring process! <a href="#">#internship #inclusivebusiness</a> <a href="#">#internship</a> <a href="#"> #hiring</a> <a href="#">#apply</a> </p>
<ul class="nav nav-stack py-3 small">
<li class="nav-item">
<a class="nav-link active" href="#!"> <i class="bi bi-hand-thumbs-up-fill pe-1"></i>Liked (56)</a>
</li>
<li class="nav-item">
<a class="nav-link" href="#!"> <i class="bi bi-chat-fill pe-1"></i>Comments (12)</a>
</li>
<!-- Card share action START -->
<li class="nav-item dropdown ms-auto">
<a class="nav-link mb-0" href="#" id="cardShareAction9" data-bs-toggle="dropdown" aria-expanded="false">
<i class="bi bi-reply-fill fa-flip-horizontal pe-1"></i>Share (3)
</a>
<!-- Card share action dropdown menu -->
<ul class="dropdown-menu dropdown-menu-end" aria-labelledby="cardShareAction9">
<li><a class="dropdown-item" href="#"> <i class="bi bi-envelope fa-fw pe-2"></i>Send via Direct Message</a></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-bookmark-check fa-fw pe-2"></i>Bookmark </a></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-link fa-fw pe-2"></i>Copy link to post</a></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-share fa-fw pe-2"></i>Share post via …</a></li>
<li><hr class="dropdown-divider"></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-pencil-square fa-fw pe-2"></i>Share to News Feed</a></li>
</ul>
</li>
<!-- Card share action END -->
</ul>
<!-- Add comment -->
<div class="d-flex mb-3">
<!-- Avatar -->
<div class="avatar avatar-xs me-2">
<img class="avatar-img rounded-circle" src="/assets/images/avatar/04.jpg" alt="">
</div>
<!-- Comment box  -->
<form class="position-relative w-100">
<textarea class="form-control pe-4 bg-light" rows="1" placeholder="Add a comment..."></textarea>
</form>
</div>
<!-- Comment wrap START -->
<ul class="comment-wrap list-unstyled ">
<!-- Comment item START -->
<li class="comment-item">
<div class="d-flex">
<!-- Avatar -->
<div class="avatar avatar-xs">
<img class="avatar-img rounded-circle" src="/assets/images/avatar/05.jpg" alt="">
</div>
<div class="ms-2">
<!-- Comment by -->
<div class="bg-light rounded-start-top-0 p-3 rounded">
<div class="d-flex justify-content-center">
<div class="me-2">
<h6 class="mb-1"> <a href="#!"> Frances Guerrero </a></h6>
<p class="small mb-0">Removed demands expense account in outward tedious do.</p>
</div>
<small>5hr</small>
</div>
</div>
<!-- Comment react -->
<ul class="nav nav-divider py-2 small">
<li class="nav-item">
<a class="nav-link" href="#!"> Like (3)</a>
</li>
<li class="nav-item">
<a class="nav-link" href="#!"> Reply</a>
</li>
<li class="nav-item">
<a class="nav-link" href="#!"> View 5 replies</a>
</li>
</ul>
</div>
</div>
</li>
</ul>
<!-- Comment wrap END -->
</div>
<!-- glightbox Albums left bar END  -->
</div>
<!-- Photo item END -->
</div>
</div>
<!-- Your photos tab END -->

<!-- Recently added tab START -->
<div class="tab-pane fade" id="tab-3">
<div class="row g-3">

<!-- Add photo START -->
<div class="col-6 col-lg-3">
<div class="border border-2 border-dashed h-100 rounded text-center d-flex align-items-center justify-content-center position-relative">
<a class="stretched-link" href="#!">
<i class="fa-solid fa-camera-retro fs-1"></i>
<h6 class="mt-2">Add photo</h6>
</a>
</div>
</div>
<!-- Add photo END -->

<!-- Photo item START -->
<div class="col-6 col-lg-3 position-relative">
<div class="position-absolute bottom-0 end-0">
<!-- Dropdown START -->
<div class="dropdown mb-2 me-3">
<a href="#" class="icon-sm bg-primary text-white rounded-circle" id="photoActionEdit9" data-bs-toggle="dropdown" aria-expanded="false">
<i class="bi bi-pencil-fill"></i>
</a>
<!-- Dropdown menu -->
<ul class="dropdown-menu dropdown-menu-end" aria-labelledby="photoActionEdit9">
<li><a class="dropdown-item" href="#"> <i class="bi bi-tag fa-fw pe-1"></i> Remove Tag</a></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-download fa-fw pe-1"></i> Download </a></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-person fa-fw pe-1"></i> Make Profile Picture</a></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-person-bounding-box fa-fw pe-1"></i> Make Cover Photo</a></li>
<li><hr class="dropdown-divider"></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-flag fa-fw pe-1"></i> Report photo</a></li>
</ul>
</div>
</div>
<!-- Dropdown END -->
<a href="/assets/images/albums/01.jpg" data-gallery="image-popup" data-glightbox="description: .custom-desc2; descPosition: left;">
<img class="rounded img-fluid" src="/assets/images/albums/01.jpg" alt="">
</a>
<!-- glightbox Albums left bar START -->
<div class="glightbox-desc custom-desc2">
<div class="d-flex align-items-center justify-content-between">
<div class="d-flex align-items-center">
<!-- Avatar -->
<div class="avatar me-2">
<img class="avatar-img rounded-circle" src="/assets/images/avatar/04.jpg" alt="">
</div>
<!-- Info -->
<div>
<div class="nav nav-divider">
<h6 class="nav-item card-title mb-0">Lori Ferguson</h6>
<span class="nav-item small"> 2hr</span>
</div>
<p class="mb-0 small">Web Developer at Webestica</p>
</div>
</div>
<!-- Card feed action dropdown START -->
<div class="dropdown">
<a href="#" class="text-secondary btn btn-secondary-soft-hover py-1 px-2" id="cardFeedAction10" data-bs-toggle="dropdown" aria-expanded="false">
<i class="bi bi-three-dots"></i>
</a>
<!-- Card feed action dropdown menu -->
<ul class="dropdown-menu dropdown-menu-end" aria-labelledby="cardFeedAction10">
<li><a class="dropdown-item" href="#"> <i class="bi bi-bookmark fa-fw pe-2"></i>Save post</a></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-person-x fa-fw pe-2"></i>Unfollow lori ferguson </a></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-x-circle fa-fw pe-2"></i>Hide post</a></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-slash-circle fa-fw pe-2"></i>Block</a></li>
<li><hr class="dropdown-divider"></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-flag fa-fw pe-2"></i>Report post</a></li>
</ul>
</div>
<!-- Card feed action dropdown END -->
</div>
<p class="mt-3 mb-0">I'm so privileged to be involved in the @bootstrap hiring process! <a href="#">#internship #inclusivebusiness</a> <a href="#">#internship</a> <a href="#"> #hiring</a> <a href="#">#apply</a> </p>
<ul class="nav nav-stack py-3 small">
<li class="nav-item">
<a class="nav-link active" href="#!"> <i class="bi bi-hand-thumbs-up-fill pe-1"></i>Liked (56)</a>
</li>
<li class="nav-item">
<a class="nav-link" href="#!"> <i class="bi bi-chat-fill pe-1"></i>Comments (12)</a>
</li>
<!-- Card share action START -->
<li class="nav-item dropdown ms-auto">
<a class="nav-link mb-0" href="#" id="cardShareAction10" data-bs-toggle="dropdown" aria-expanded="false">
<i class="bi bi-reply-fill fa-flip-horizontal pe-1"></i>Share (3)
</a>
<!-- Card share action dropdown menu -->
<ul class="dropdown-menu dropdown-menu-end" aria-labelledby="cardShareAction10">
<li><a class="dropdown-item" href="#"> <i class="bi bi-envelope fa-fw pe-2"></i>Send via Direct Message</a></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-bookmark-check fa-fw pe-2"></i>Bookmark </a></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-link fa-fw pe-2"></i>Copy link to post</a></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-share fa-fw pe-2"></i>Share post via …</a></li>
<li><hr class="dropdown-divider"></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-pencil-square fa-fw pe-2"></i>Share to News Feed</a></li>
</ul>
</li>
<!-- Card share action END -->
</ul>
<!-- Add comment -->
<div class="d-flex mb-3">
<!-- Avatar -->
<div class="avatar avatar-xs me-2">
<img class="avatar-img rounded-circle" src="/assets/images/avatar/04.jpg" alt="">
</div>
<!-- Comment box  -->
<form class="position-relative w-100">
<textarea class="form-control pe-4 bg-light" rows="1" placeholder="Add a comment..."></textarea>
</form>
</div>
<!-- Comment wrap START -->
<ul class="comment-wrap list-unstyled ">
<!-- Comment item START -->
<li class="comment-item">
<div class="d-flex">
<!-- Avatar -->
<div class="avatar avatar-xs">
<img class="avatar-img rounded-circle" src="/assets/images/avatar/05.jpg" alt="">
</div>
<div class="ms-2">
<!-- Comment by -->
<div class="bg-light rounded-start-top-0 p-3 rounded">
<div class="d-flex justify-content-center">
<div class="me-2">
<h6 class="mb-1"> <a href="#!"> Frances Guerrero </a></h6>
<p class="small mb-0">Removed demands expense account in outward tedious do.</p>
</div>
<small>5hr</small>
</div>
</div>
<!-- Comment react -->
<ul class="nav nav-divider py-2 small">
<li class="nav-item">
<a class="nav-link" href="#!"> Like (3)</a>
</li>
<li class="nav-item">
<a class="nav-link" href="#!"> Reply</a>
</li>
<li class="nav-item">
<a class="nav-link" href="#!"> View 5 replies</a>
</li>
</ul>
</div>
</div>
</li>
</ul>
<!-- Comment wrap END -->
</div>
<!-- glightbox Albums left bar END  -->
</div>
<!-- Photo item END -->

<!-- Photo item START -->
<div class="col-6 col-lg-3 position-relative">
<div class="position-absolute bottom-0 end-0">
<!-- Dropdown START -->
<div class="dropdown mb-2 me-3">
<a href="#" class="icon-sm bg-primary text-white rounded-circle" id="photoActionEdit10" data-bs-toggle="dropdown" aria-expanded="false">
<i class="bi bi-pencil-fill"></i>
</a>
<!-- Dropdown menu -->
<ul class="dropdown-menu dropdown-menu-end" aria-labelledby="photoActionEdit10">
<li><a class="dropdown-item" href="#"> <i class="bi bi-tag fa-fw pe-1"></i> Remove Tag</a></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-download fa-fw pe-1"></i> Download </a></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-person fa-fw pe-1"></i> Make Profile Picture</a></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-person-bounding-box fa-fw pe-1"></i> Make Cover Photo</a></li>
<li><hr class="dropdown-divider"></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-flag fa-fw pe-1"></i> Report photo</a></li>
</ul>
</div>
</div>
<!-- Dropdown END -->
<a href="/assets/images/albums/02.jpg" data-gallery="image-popup" data-glightbox="description: .custom-desc2; descPosition: left;">
<img class="rounded img-fluid" src="/assets/images/albums/02.jpg" alt="">
</a>
<!-- glightbox Albums left bar START -->
<div class="glightbox-desc custom-desc2">
<div class="d-flex align-items-center justify-content-between">
<div class="d-flex align-items-center">
<!-- Avatar -->
<div class="avatar me-2">
<img class="avatar-img rounded-circle" src="/assets/images/avatar/04.jpg" alt="">
</div>
<!-- Info -->
<div>
<div class="nav nav-divider">
<h6 class="nav-item card-title mb-0">Lori Ferguson</h6>
<span class="nav-item small"> 2hr</span>
</div>
<p class="mb-0 small">Web Developer at Webestica</p>
</div>
</div>
<!-- Card feed action dropdown START -->
<div class="dropdown">
<a href="#" class="text-secondary btn btn-secondary-soft-hover py-1 px-2" id="cardFeedAction11" data-bs-toggle="dropdown" aria-expanded="false">
<i class="bi bi-three-dots"></i>
</a>
<!-- Card feed action dropdown menu -->
<ul class="dropdown-menu dropdown-menu-end" aria-labelledby="cardFeedAction11">
<li><a class="dropdown-item" href="#"> <i class="bi bi-bookmark fa-fw pe-2"></i>Save post</a></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-person-x fa-fw pe-2"></i>Unfollow lori ferguson </a></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-x-circle fa-fw pe-2"></i>Hide post</a></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-slash-circle fa-fw pe-2"></i>Block</a></li>
<li><hr class="dropdown-divider"></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-flag fa-fw pe-2"></i>Report post</a></li>
</ul>
</div>
<!-- Card feed action dropdown END -->
</div>
<p class="mt-3 mb-0">I'm so privileged to be involved in the @bootstrap hiring process! <a href="#">#internship #inclusivebusiness</a> <a href="#">#internship</a> <a href="#"> #hiring</a> <a href="#">#apply</a> </p>
<ul class="nav nav-stack py-3 small">
<li class="nav-item">
<a class="nav-link active" href="#!"> <i class="bi bi-hand-thumbs-up-fill pe-1"></i>Liked (56)</a>
</li>
<li class="nav-item">
<a class="nav-link" href="#!"> <i class="bi bi-chat-fill pe-1"></i>Comments (12)</a>
</li>
<!-- Card share action START -->
<li class="nav-item dropdown ms-auto">
<a class="nav-link mb-0" href="#" id="cardShareAction11" data-bs-toggle="dropdown" aria-expanded="false">
<i class="bi bi-reply-fill fa-flip-horizontal pe-1"></i>Share (3)
</a>
<!-- Card share action dropdown menu -->
<ul class="dropdown-menu dropdown-menu-end" aria-labelledby="cardShareAction11">
<li><a class="dropdown-item" href="#"> <i class="bi bi-envelope fa-fw pe-2"></i>Send via Direct Message</a></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-bookmark-check fa-fw pe-2"></i>Bookmark </a></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-link fa-fw pe-2"></i>Copy link to post</a></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-share fa-fw pe-2"></i>Share post via …</a></li>
<li><hr class="dropdown-divider"></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-pencil-square fa-fw pe-2"></i>Share to News Feed</a></li>
</ul>
</li>
<!-- Card share action END -->
</ul>
<!-- Add comment -->
<div class="d-flex mb-3">
<!-- Avatar -->
<div class="avatar avatar-xs me-2">
<img class="avatar-img rounded-circle" src="/assets/images/avatar/04.jpg" alt="">
</div>
<!-- Comment box  -->
<form class="position-relative w-100">
<textarea class="form-control pe-4 bg-light" rows="1" placeholder="Add a comment..."></textarea>
</form>
</div>
<!-- Comment wrap START -->
<ul class="comment-wrap list-unstyled ">
<!-- Comment item START -->
<li class="comment-item">
<div class="d-flex">
<!-- Avatar -->
<div class="avatar avatar-xs">
<img class="avatar-img rounded-circle" src="/assets/images/avatar/05.jpg" alt="">
</div>
<div class="ms-2">
<!-- Comment by -->
<div class="bg-light rounded-start-top-0 p-3 rounded">
<div class="d-flex justify-content-center">
<div class="me-2">
<h6 class="mb-1"> <a href="#!"> Frances Guerrero </a></h6>
<p class="small mb-0">Removed demands expense account in outward tedious do.</p>
</div>
<small>5hr</small>
</div>
</div>
<!-- Comment react -->
<ul class="nav nav-divider py-2 small">
<li class="nav-item">
<a class="nav-link" href="#!"> Like (3)</a>
</li>
<li class="nav-item">
<a class="nav-link" href="#!"> Reply</a>
</li>
<li class="nav-item">
<a class="nav-link" href="#!"> View 5 replies</a>
</li>
</ul>
</div>
</div>
</li>
</ul>
<!-- Comment wrap END -->
</div>
<!-- glightbox Albums left bar END  -->
</div>
<!-- Photo item END -->

<!-- Photo item START -->
<div class="col-6 col-lg-3 position-relative">
<div class="position-absolute bottom-0 end-0">
<!-- Dropdown START -->
<div class="dropdown mb-2 me-3">
<a href="#" class="icon-sm bg-primary text-white rounded-circle" id="photoActionEdit12" data-bs-toggle="dropdown" aria-expanded="false">
<i class="bi bi-pencil-fill"></i>
</a>
<!-- Dropdown menu -->
<ul class="dropdown-menu dropdown-menu-end" aria-labelledby="photoActionEdit12">
<li><a class="dropdown-item" href="#"> <i class="bi bi-tag fa-fw pe-1"></i> Remove Tag</a></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-download fa-fw pe-1"></i> Download </a></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-person fa-fw pe-1"></i> Make Profile Picture</a></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-person-bounding-box fa-fw pe-1"></i> Make Cover Photo</a></li>
<li><hr class="dropdown-divider"></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-flag fa-fw pe-1"></i> Report photo</a></li>
</ul>
</div>
</div>
<!-- Dropdown END -->
<a href="/assets/images/albums/03.jpg" data-gallery="image-popup" data-glightbox="description: .custom-desc2; descPosition: left;">
<img class="rounded img-fluid" src="/assets/images/albums/03.jpg" alt="">
</a>
<!-- glightbox Albums left bar START -->
<div class="glightbox-desc custom-desc2">
<div class="d-flex align-items-center justify-content-between">
<div class="d-flex align-items-center">
<!-- Avatar -->
<div class="avatar me-2">
<img class="avatar-img rounded-circle" src="/assets/images/avatar/04.jpg" alt="">
</div>
<!-- Info -->
<div>
<div class="nav nav-divider">
<h6 class="nav-item card-title mb-0">Lori Ferguson</h6>
<span class="nav-item small"> 2hr</span>
</div>
<p class="mb-0 small">Web Developer at Webestica</p>
</div>
</div>
<!-- Card feed action dropdown START -->
<div class="dropdown">
<a href="#" class="text-secondary btn btn-secondary-soft-hover py-1 px-2" id="cardFeedAction12" data-bs-toggle="dropdown" aria-expanded="false">
<i class="bi bi-three-dots"></i>
</a>
<!-- Card feed action dropdown menu -->
<ul class="dropdown-menu dropdown-menu-end" aria-labelledby="cardFeedAction12">
<li><a class="dropdown-item" href="#"> <i class="bi bi-bookmark fa-fw pe-2"></i>Save post</a></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-person-x fa-fw pe-2"></i>Unfollow lori ferguson </a></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-x-circle fa-fw pe-2"></i>Hide post</a></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-slash-circle fa-fw pe-2"></i>Block</a></li>
<li><hr class="dropdown-divider"></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-flag fa-fw pe-2"></i>Report post</a></li>
</ul>
</div>
<!-- Card feed action dropdown END -->
</div>
<p class="mt-3 mb-0">I'm so privileged to be involved in the @bootstrap hiring process! <a href="#">#internship #inclusivebusiness</a> <a href="#">#internship</a> <a href="#"> #hiring</a> <a href="#">#apply</a> </p>
<ul class="nav nav-stack py-3 small">
<li class="nav-item">
<a class="nav-link active" href="#!"> <i class="bi bi-hand-thumbs-up-fill pe-1"></i>Liked (56)</a>
</li>
<li class="nav-item">
<a class="nav-link" href="#!"> <i class="bi bi-chat-fill pe-1"></i>Comments (12)</a>
</li>
<!-- Card share action START -->
<li class="nav-item dropdown ms-auto">
<a class="nav-link mb-0" href="#" id="cardShareAction12" data-bs-toggle="dropdown" aria-expanded="false">
<i class="bi bi-reply-fill fa-flip-horizontal pe-1"></i>Share (3)
</a>
<!-- Card share action dropdown menu -->
<ul class="dropdown-menu dropdown-menu-end" aria-labelledby="cardShareAction12">
<li><a class="dropdown-item" href="#"> <i class="bi bi-envelope fa-fw pe-2"></i>Send via Direct Message</a></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-bookmark-check fa-fw pe-2"></i>Bookmark </a></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-link fa-fw pe-2"></i>Copy link to post</a></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-share fa-fw pe-2"></i>Share post via …</a></li>
<li><hr class="dropdown-divider"></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-pencil-square fa-fw pe-2"></i>Share to News Feed</a></li>
</ul>
</li>
<!-- Card share action END -->
</ul>
<!-- Add comment -->
<div class="d-flex mb-3">
<!-- Avatar -->
<div class="avatar avatar-xs me-2">
<img class="avatar-img rounded-circle" src="/assets/images/avatar/04.jpg" alt="">
</div>
<!-- Comment box  -->
<form class="position-relative w-100">
<textarea class="form-control pe-4 bg-light" rows="1" placeholder="Add a comment..."></textarea>
</form>
</div>
<!-- Comment wrap START -->
<ul class="comment-wrap list-unstyled ">
<!-- Comment item START -->
<li class="comment-item">
<div class="d-flex">
<!-- Avatar -->
<div class="avatar avatar-xs">
<img class="avatar-img rounded-circle" src="/assets/images/avatar/05.jpg" alt="">
</div>
<div class="ms-2">
<!-- Comment by -->
<div class="bg-light rounded-start-top-0 p-3 rounded">
<div class="d-flex justify-content-center">
<div class="me-2">
<h6 class="mb-1"> <a href="#!"> Frances Guerrero </a></h6>
<p class="small mb-0">Removed demands expense account in outward tedious do.</p>
</div>
<small>5hr</small>
</div>
</div>
<!-- Comment react -->
<ul class="nav nav-divider py-2 small">
<li class="nav-item">
<a class="nav-link" href="#!"> Like (3)</a>
</li>
<li class="nav-item">
<a class="nav-link" href="#!"> Reply</a>
</li>
<li class="nav-item">
<a class="nav-link" href="#!"> View 5 replies</a>
</li>
</ul>
</div>
</div>
</li>
</ul>
<!-- Comment wrap END -->
</div>
<!-- glightbox Albums left bar END  -->
</div>
<!-- Photo item END -->
</div>
</div>
<!-- Recently added tab END -->

<!-- Family tab START -->
<div class="tab-pane fade text-center" id="tab-4">
<div class="my-sm-5 py-sm-5">
<i class="display-1 text-muted bi bi-file-earmark-x"> </i>
<h4 class="mt-2 mb-3 text-body">No photos or videos</h4>
<button class="btn btn-primary-soft btn-sm" data-bs-toggle="modal" data-bs-target="#modalCreateAlbum"> Click here to add </button>
</div>
</div>
<!-- Family tab END -->

<!-- Albums START -->
<div class="tab-pane fade" id="tab-5">
<div class="row g-3">

<!-- Album item START -->
<div class="col-6 col-lg-3">
<!-- Album poster -->
<a href="#">
<img class="rounded img-fluid" src="/assets/images/albums/01.jpg" alt="">
</a>
<!-- Album name -->
<div class="hstack mt-3">
<div>
<h6 class="mb-0"> <a href="#!"> Cover Photos </a> </h6>
<a class="text-secondary small" href="#!">5 Items</a>
</div>
<!-- Dropdown START -->
<div class="dropdown ms-auto">
<a href="#" class="icon-sm bg-light text-secondary rounded-circle" id="photoActionEdit17" data-bs-toggle="dropdown" aria-expanded="false">
<i class="bi bi-three-dots"></i>
</a>
<!-- Dropdown menu -->
<ul class="dropdown-menu dropdown-menu-end" aria-labelledby="photoActionEdit17">
<li><a class="dropdown-item" href="#"> <i class="bi bi-pencil fa-fw pe-1"></i> Edit</a></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-download fa-fw pe-1"></i> Download </a></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-trash fa-fw pe-1"></i> Delete</a></li>
<li><hr class="dropdown-divider"></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-flag fa-fw pe-1"></i> Report album</a></li>
</ul>
</div>
<!-- Dropdown END -->
</div>
</div>
<!-- Album item END -->

<!-- Album item START -->
<div class="col-6 col-lg-3">
<!-- Album poster -->
<a href="#">
<img class="rounded img-fluid" src="/assets/images/albums/02.jpg" alt="">
</a>
<!-- Album name -->
<div class="hstack mt-3">
<div>
<h6 class="mb-0"> <a href="#!"> Profile pictures </a> </h6>
<a class="text-secondary small" href="#!">20 Items</a>
</div>
<!-- Dropdown START -->
<div class="dropdown ms-auto">
<a href="#" class="icon-sm bg-light text-secondary rounded-circle" id="albumActionSetting2" data-bs-toggle="dropdown" aria-expanded="false">
<i class="bi bi-three-dots"></i>
</a>
<!-- Dropdown menu -->
<ul class="dropdown-menu dropdown-menu-end" aria-labelledby="albumActionSetting2">
<li><a class="dropdown-item" href="#"> <i class="bi bi-pencil fa-fw pe-1"></i> Edit</a></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-download fa-fw pe-1"></i> Download </a></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-trash fa-fw pe-1"></i> Delete</a></li>
<li><hr class="dropdown-divider"></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-flag fa-fw pe-1"></i> Report album</a></li>
</ul>
</div>
<!-- Dropdown END -->
</div>
</div>
<!-- Album item END -->

<!-- Album item START -->
<div class="col-6 col-lg-3">
<!-- Album poster -->
<a href="#">
<img class="rounded img-fluid" src="/assets/images/albums/03.jpg" alt="">
</a>
<!-- Album name -->
<div class="hstack mt-3">
<div>
<h6 class="mb-0"> <a href="#!"> Untitled pictures </a> </h6>
<a class="text-secondary small" href="#!">12 Items</a>
</div>
<!-- Dropdown START -->
<div class="dropdown ms-auto">
<a href="#" class="icon-sm bg-light text-secondary rounded-circle" id="albumActionSetting3" data-bs-toggle="dropdown" aria-expanded="false">
<i class="bi bi-three-dots"></i>
</a>
<!-- Dropdown menu -->
<ul class="dropdown-menu dropdown-menu-end" aria-labelledby="albumActionSetting3">
<li><a class="dropdown-item" href="#"> <i class="bi bi-pencil fa-fw pe-1"></i> Edit</a></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-download fa-fw pe-1"></i> Download </a></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-trash fa-fw pe-1"></i> Delete</a></li>
<li><hr class="dropdown-divider"></li>
<li><a class="dropdown-item" href="#"> <i class="bi bi-flag fa-fw pe-1"></i> Report album</a></li>
</ul>
</div>
<!-- Dropdown END -->
</div>
</div>
<!-- Album item END -->
</div>
</div>
<!-- Albums END -->
</div>

<!-- Album Tab content END -->
</div>
<!-- Card body END -->
</div>
<!-- Card END -->
</div>
</div> <!-- Row END -->
</div>
<!-- Container END -->