---
slug: "/card"
date: "2019-05-04"
title: "Elements > Card"
---
<!-- CSS only -->
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3" crossorigin="anonymous">
<link rel="stylesheet" href="../../../../../../../raaghu/src/assets/css/style-elements.css">
<link rel="stylesheet" href="../../../../../../../raaghu/src/assets/css/main.css">




#### Card

<p class="">A card is a small rectangular module with images and text. It is an entry point for users to learn more details</p>

<section class="py-4">
    <h6>Default</h6>
    <div class="py-3">
      <div class="cust-tabs">
        <ul class="nav nav-tabs" id="myTab" role="tablist">
          <li class="nav-item" role="presentation">
            <button class="nav-link active" id="PreviewBasic-tab" data-bs-toggle="tab" data-bs-target="#PreviewBasic" type="button" role="tab" aria-controls="PreviewBasic" aria-selected="true">Preview </button>
          </li>
          <li class="nav-item" role="presentation">
            <button class="nav-link" id="AngularBasic-tab" data-bs-toggle="tab" data-bs-target="#AngularBasic" type="button" role="tab" aria-controls="AngularBasic" aria-selected="false"><i class="bi bi-code-slash" style="font-size:1.0rem"></i>Angular</button>
          </li>
          <li class="nav-item" role="presentation">
            <button class="nav-link" id="ReactBasic-tab" data-bs-toggle="tab" data-bs-target="#ReactBasic" type="button" role="tab" aria-controls="ReactBasic" aria-selected="false"><i class="bi bi-code-slash" style="font-size:1.0rem"></i>React</button>
          </li>
        </ul>
      </div>
      <div class="tab-content card border" id="myTabContent">
        <div class="tab-pane fade show active" id="PreviewBasic" role="tabpanel" aria-labelledby="PreviewBasic-tab">
         <div class="contents  p-5">
              <div class="row">
               <div class="col-md-12">
                <img src="/images/card-basic.png" class="img-fluid w-100"></div>
              </div>
             </div>
        </div>
        <div class="tab-pane fade show" id="AngularBasic" role="tabpanel" aria-labelledby="AngularBasic-tab">
          <div class="contents bg-code">
<div class="row m-0">

```html
<rds-card
  [topBottomPadding]="topBottomPadding"
  [sidePadding]="sidePadding"
  [showHeader]="showHeader"
  [showBody]="showBody"
  [showFooter]="showFooter"
  [borderColor]="borderColor"
>
  <div header class="card-header pt-3 px-3">
    <h5>Header Title</h5>
  </div>
  <div body>
    <p>
      Some quick example text to build on the card title and make up the bulk of
      the card's content
    </p>
  </div>
  <div footer>
    <a href="#" class="btn btn-primary">Go somewhere</a>
  </div>
</rds-card>
```
</div>
</div>
  </div>
  <!-- React start -->

  <div class="tab-pane fade show" id="ReactBasic" role="tabpanel" aria-labelledby="ReactBasic-tab">
    <div class="contents bg-code">

<div class="row m-0">

```html
<RdsCard
  borderColor=""
  buttonLabel="Button"
  cardText="Some quick example text to build on the card title and make up the bulk of the card's content."
  cardTitle="Card title"
  colorVariant="primary"
  showFooter
/>
```

</div>
          </div>
        </div>
        <!-- React end -->
        </div>
      </div>
    </div>
  </section>
   


   <section class="py-4">
    <h6>Avatar</h6>
    <div class="py-3">
      <div class="cust-tabs">
         <ul class="nav nav-tabs" id="myTab" role="tablist">
          <li class="nav-item" role="presentation">
            <button class="nav-link active" id="PreviewWithAvtar-tab" data-bs-toggle="tab" data-bs-target="#PreviewWithAvtar" type="button" role="tab" aria-controls="PreviewWithAvtar" aria-selected="true">Preview </button>
          </li>
          <li class="nav-item" role="presentation">
            <button class="nav-link" id="AngularWithAvtar-tab" data-bs-toggle="tab" data-bs-target="#AngularWithAvtar" type="button" role="tab" aria-controls="AngularBasic" aria-selected="false"><i class="bi bi-code-slash" style="font-size:1.0rem"></i>Angular</button>
          </li>
           <li class="nav-item" role="presentation">
            <button class="nav-link" id="ReactAvatar-tab" data-bs-toggle="tab" data-bs-target="#ReactAvatar" type="button" role="tab" aria-controls="ReactAvatar" aria-selected="false"><i class="bi bi-code-slash" style="font-size:1.0rem"></i>React</button>
          </li>
        </ul>
      </div>
      <div class="tab-content card border" id="myTabContent">
        <div class="tab-pane fade show active" id="PreviewWithAvtar" role="tabpanel" aria-labelledby="PreviewWithAvtar-tab">
         <div class="contents  p-5">
             <div class="row">
             <div class="col-md-12">
                  <img src="/images/card-avatar.png"class="img-fluid w-50"> 
                  </div>                                
           </div>               
         </div>
        </div>
        <div class="tab-pane fade show" id="AngularWithAvtar" role="tabpanel" aria-labelledby="AngularWithAvtar-tab">
          <div class="contents bg-code">
<div class="row m-0">

```html
 <rds-card
  [topBottomPadding]="topBottomPadding"
  [sidePadding]="sidePadding"
  [showHeader]="showHeader"
  [showBody]="showBody"
  [showFooter]="showFooter"
  [colorVariant]="colorVariant"
  [borderColor]="borderColor"
>
  <div header>
    <div class="banner-image1 position-relative">
      <div>
        <img
          src="https://picsum.photos/seed/picsum/1200/600"
          class="card-img-top"
          alt=""
        />
      </div>
      <div class="position-absolute avatar-pic">
        <rds-avatar
          [withProfilePic]="true"
          size="large"
          [roundedPills]="false"
          [profilePic]="'https://placekitten.com/300/300'"
          [roundedAvatar]="true"
        ></rds-avatar>
      </div>
    </div>
  </div>
  <div body class="pt-3">
    <h5>Header Title</h5>
    <p>
      Some quick example text to build on the card title and make up the bulk of
      the card's content
    </p>
  </div>
  <div footer>
    <a href="#" class="btn btn-primary">Go somewhere</a>
  </div>
</rds-card>
```
</div>
</div>
  </div>
  
  <!-- React start -->

  <div class="tab-pane fade show" id="ReactAvatar" role="tabpanel" aria-labelledby="ReactAvatar-tab">
    <div class="contents bg-code">

<div class="row m-0">

```html
<RdsCard
  avatarUrl="https://placekitten.com/300/300"
  buttonLabel="Button"
  cardText="Some quick example text to build on the card title and make up the bulk of the card's content."
  cardTitle="Card title"
  colorVariant="primary"
  imageUrl="https://picsum.photos/seed/picsum/1200/600"
  isAvatar
  isImage
  showFooter
/>
```

</div>
          </div>
        </div>
        <!-- React end -->
        </div>
      </div>
    </div>
  </section>

<section class="py-4">
    <h6>Card with Image</h6>
    <div class="py-3">
      <div class="cust-tabs">
        <ul class="nav nav-tabs" id="myTab" role="tablist">
          <li class="nav-item" role="presentation">
            <button class="nav-link active" id="PreviewImage-tab" data-bs-toggle="tab" data-bs-target="#PreviewImage" type="button" role="tab" aria-controls="PreviewImage" aria-selected="true">Preview </button>
          </li>
          <li class="nav-item" role="presentation">
            <button class="nav-link" id="AngularImage-tab" data-bs-toggle="tab" data-bs-target="#AngularImage" type="button" role="tab" aria-controls="AngularImage" aria-selected="false"><i class="bi bi-code-slash" style="font-size:1.0rem"></i>Angular</button>
          </li>
           <li class="nav-item" role="presentation">
            <button class="nav-link" id="ReactCardImg-tab" data-bs-toggle="tab" data-bs-target="#ReactCardImg" type="button" role="tab" aria-controls="ReactCardImg" aria-selected="false"><i class="bi bi-code-slash" style="font-size:1.0rem"></i>React</button>
          </li>
        </ul>
      </div>
      <div class="tab-content card border" id="myTabContent">
        <div class="tab-pane fade show active" id="PreviewImage" role="tabpanel" aria-labelledby="PreviewImage-tab">
         <div class="contents  p-5">
              <div class="row">
               <div class="col-md-12">
                <img src="/images/card-with-image.png" class="img-fluid w-50"></div>
              </div>
             </div>
        </div>
        <div class="tab-pane fade show" id="AngularImage" role="tabpanel" aria-labelledby="AngularImage-tab">
          <div class="contents bg-code">
<div class="row m-0">

```html
<rds-card
  [topBottomPadding]="topBottomPadding"
  [sidePadding]="sidePadding"
  [showHeader]="showHeader"
  [showBody]="showBody"
  [showFooter]="showFooter"
  [borderColor]="borderColor"
  [colorVariant]="colorVariant"
>
  <div header>
    <img
      src="https://picsum.photos/seed/picsum/1200/600"
      class="card-img-top"
      alt=""
    />
  </div>
  <div body>
    <h5>Header Title</h5>
    <p>
      Some quick example text to build on the card title and make up the bulk of
      the card's content
    </p>
  </div>
  <div footer>
    <a href="#" class="btn btn-primary">Go somewhere</a>
  </div>
</rds-card>
```
</div>
</div>
  </div>
   <!-- React start -->

  <div class="tab-pane fade show" id="ReactCardImg" role="tabpanel" aria-labelledby="ReactCardImg-tab">
    <div class="contents bg-code">

<div class="row m-0">

```html
<RdsCard
  buttonLabel="Button"
  cardText="Some quick example text to build on the card title and make up the bulk of the card's content."
  cardTitle="Card title"
  colorVariant="primary"
  imageUrl="https://picsum.photos/seed/picsum/1200/600"
  isImage
  showFooter
/>
```

</div>
          </div>
        </div>
        <!-- React end -->
        </div>
      </div>
    </div>
  </section>
   


<section class="py-4">
    <h6>With Centered Avatar</h6>
    <div class="py-3">
      <div class="cust-tabs">
        <ul class="nav nav-tabs" id="myTab" role="tablist">
          <li class="nav-item" role="presentation">
            <button class="nav-link active" id="PreviewWithAvtarCenter-tab" data-bs-toggle="tab" data-bs-target="#PreviewWithAvtarCenter" type="button" role="tab" aria-controls="PreviewWithAvtarCenter" aria-selected="true">Preview </button>
          </li>
          <li class="nav-item" role="presentation">
            <button class="nav-link" id="AngularWithAvtarCenter-tab" data-bs-toggle="tab" data-bs-target="#AngularWithAvtarCenter" type="button" role="tab" aria-controls="AngularWithAvtarCenter" aria-selected="false"><i class="bi bi-code-slash" style="font-size:1.0rem"></i>Angular</button>
          </li>
           <li class="nav-item" role="presentation">
            <button class="nav-link" id="ReactCenterAvatar-tab" data-bs-toggle="tab" data-bs-target="#ReactCenterAvatar" type="button" role="tab" aria-controls="ReactCenterAvatar" aria-selected="false"><i class="bi bi-code-slash" style="font-size:1.0rem"></i>React</button>
          </li>
        </ul>
      </div>
      <div class="tab-content card border" id="myTabContent">
        <div class="tab-pane fade show active" id="PreviewWithAvtarCenter" role="tabpanel" aria-labelledby="PreviewWithAvtarCenter-tab">
         <div class="contents p-5">
              <div class="tab-pane fade show active" id="PreviewWithAvtarCenter" role="tabpanel" aria-labelledby="preview-tab">
   <div class="contents  p-5">
    <div class="row">
    <div class="col-md-12">
         <img src="/images/card-avatar-center.png"class="img-fluid w-50">  
         </div> 
   </div> 
   </div>
  </div>
  </div>
      </div>
        <div class="tab-pane fade show" id="AngularWithAvtarCenter" role="tabpanel" aria-labelledby="AngularWithAvtarCenter-tab">
          <div class="contents bg-code">
<div class="row m-0">

```html
  <rds-card
  [topBottomPadding]="topBottomPadding"
  [sidePadding]="sidePadding"
  [showHeader]="showHeader"
  [showBody]="showBody"
  [showFooter]="showFooter"
  [colorVariant]="colorVariant"
  [borderColor]="borderColor"
>
  <div header class="">
    <div class="banner-image1 position-relative">
      <div>
        <img
          src="https://picsum.photos/seed/picsum/1200/600"
          class="card-img-top"
          alt=""
        />
      </div>
      <div class="position-relative avatar-pic2 d-flex justify-content-center">
        <rds-avatar
          [withProfilePic]="true"
          size="large"
          [roundedPills]="false"
          [profilePic]="'https://placekitten.com/300/300'"
          [roundedAvatar]="true"
        ></rds-avatar>
      </div>
    </div>
  </div>
  <div body>
    <h5>Header Title</h5>
    <p>
      Some quick example text to build on the card title and make up the bulk of
      the card's content
    </p>
  </div>
  <div footer>
    <a href="#" class="btn btn-primary">Go somewhere</a>
  </div>
</rds-card>
```
</div>

  </div>
        </div>
        <!-- React start -->
        <div class="tab-pane fade show" id="ReactCenterAvatar" role="tabpanel" aria-labelledby="ReactCenterAvatar-tab">
          <div class="contents bg-code">
    <div class="row m-0">

```html
<RdsCard
  avatarUrl="https://placekitten.com/300/300"
  buttonLabel="Button"
  cardText="Some quick example text to build on the card title and make up the bulk of the card's content."
  cardTitle="Card title"
  centerAlign
  colorVariant="primary"
  imageUrl="https://picsum.photos/seed/picsum/1200/600"
  isAvatar
  isImage
  showFooter
/>
```

</div>
          </div>
        </div>
      <!-- React End -->
      </div>
    </div>
  </section>



<section class="py-4">
<h6>Skeleton/Specifications</h6>
<div class="py-3">
 <div class="card border p-5">
  <div class="row">
      <div class="col-md-12">
        <img src="/images/card-skeleton.png" class="img-fluid">
     </div>
   </div>
   </div>
 </div>
</div>	

  </section>
  
<!-- JavaScript Bundle with Popper -->
<script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.2/dist/umd/popper.min.js" integrity="sha384-IQsoLXl5PILFhosVNubq5LC7Qb9DXgDA9i+tQ8Zj3iwWAwPtgFTxbJ8NT4GN1R8p" crossorigin="anonymous"></script><script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.min.js" integrity="sha384-cVKIPhGWiC2Al4u+LWgxfKTRIcfu0JTxR+EQDz/bgldoEyl4H0zUF0QKbrJ0EcQF" crossorigin="anonymous"></script>

