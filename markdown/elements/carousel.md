---
slug: "/carousel"
date: "2019-05-04"
title: "Elements > Carousel"
---
<!-- CSS only -->
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3" crossorigin="anonymous">
<link rel="stylesheet" href="../../../../../../../raaghu/src/assets/css/style-elements.css">
<link rel="stylesheet" href="../../../../../../../raaghu/src/assets/css/main.css">


#### Carousel

<p class="">A carousel is a slideshow that cycles through a collection of pictures, text, or unique markup.</p>
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
                     <img src="/images/carousel-basic.png" class="img-fluid w-50">
                 </div>                           
           </div>
                       
  </div>
        </div>
        <div class="tab-pane fade show" id="AngularBasic" role="tabpanel" aria-labelledby="AngularBasic-tab">
          <div class="contents bg-code">
<div class="row m-0">

```html
<rds-carousel
  [crossFade]="true"
  [indicators]="true"
  [controls]="true"
  display_type="basic"
  [imageItem]="imageItem"
></rds-carousel>
```
</div>
</div>
  </div>
       <!-- React start -->
        <div class="tab-pane fade show" id="ReactBasic" role="tabpanel" aria-labelledby="ReactBasic-tab">
          <div class="contents bg-code">
    <div class="row m-0">

```html
<RdsCarousel
  Indicators
  carouselItems={[
    {
      id: 1,
      imgUrl: 'https://cdn.londonandpartners.com/visit/london-organisations/tower-bridge/86830-640x360-tower-bridge-640.jpg',
      name: 'Sam Smith',
      roleName: 'Product Manager',
      subTitle: 'Nulla metus metus ullamcorper vel tincidunt set euismod nibh quisque volutpat condimentum veilt class patent taciti sociosqu and litara ad litora torquent per conubia nastra.'
    },
    {
      id: 2,
      imgUrl: 'https://cdn.londonandpartners.com/-/media/images/london/visit/things-to-do/sightseeing/london-attractions/coca-cola-london-eye/the-london-eye-2-640x360.jpg?mw=640&hash=F7D574072DAD523443450DF57E3B91530064E4EE',
      name: 'king John',
      roleName: 'Tech Lead',
      subTitle: 'this is the caption section were u can add the caption for the image'
    }
  ]}
  controls
  crossFade
/>
```

</div>
          </div>
        </div>
      <!-- React End -->
        </div>
      </div>
    </div>
  </section>

  <section class="py-4">
    <h6>Advance</h6>
    <div class="py-3">
      <div class="cust-tabs">
        <ul class="nav nav-tabs" id="myTab" role="tablist">
          <li class="nav-item" role="presentation">
            <button class="nav-link active" id="PreviewAdvance-tab" data-bs-toggle="tab" data-bs-target="#PreviewAdvance" type="button" role="tab" aria-controls="PreviewBasic" aria-selected="true">Preview </button>
          </li>
          <li class="nav-item" role="presentation">
            <button class="nav-link" id="AngularAdvance-tab" data-bs-toggle="tab" data-bs-target="#AngularAdvance" type="button" role="tab" aria-controls="AngularBasic" aria-selected="false"><i class="bi bi-code-slash" style="font-size:1.0rem"></i>Angular</button>
          </li>
           <li class="nav-item" role="presentation">
            <button class="nav-link" id="ReactAdvance-tab" data-bs-toggle="tab" data-bs-target="#ReactAdvance" type="button" role="tab" aria-controls="ReactAdvance" aria-selected="false"><i class="bi bi-code-slash" style="font-size:1.0rem"></i>React</button>
          </li>
        </ul>
      </div>
      <div class="tab-content card border" id="myTabContent">
        <div class="tab-pane fade show active" id="PreviewAdvance" role="tabpanel" aria-labelledby="PreviewBasic-tab">
         <div class="contents  p-5">
              <div class="row">
                 <div class="col-md-12">
                     <img src="/images/carousel-advanced.png" class="img-fluid">
                 </div>                           
           </div>
                       
  </div>
        </div>
        <div class="tab-pane fade show" id="AngularAdvance" role="tabpanel" aria-labelledby="AngularBasic-tab">
          <div class="contents bg-code">
<div class="row m-0">

```html
<rds-carousel
  [crossFade]="true"
  [indicators]="true"
  [controls]="true"
  display_type="advance"
  [carousalItem]="carousalItem"
></rds-carousel>
</div>
```
</div>
</div>
  </div>
     <!-- React start -->
        <div class="tab-pane fade show" id="ReactAdvance" role="tabpanel" aria-labelledby="ReactAdvance-tab">
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
    </div>
  </section>
  
###### Skeleton/Specifications
<div class="py-3">
 <div class="card border p-5">
  <div class="row">
      <div class="col-md-12">
        <img src="/images/carousel-skeleton.png" class="img-fluid">
     </div>
   </div>
   </div>
 </div>
</div>	