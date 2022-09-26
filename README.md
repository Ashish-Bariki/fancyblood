#A tiny css library

    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/fancyblood@1.0.3/package/dist/fancyblood.min.css">
    
    <nav class="navbar-error p-0">
        <div class="contains text-white">
            <a href="#" class="nav-logo">fancybl</a>
            <div class="nav-link">
                <a href=""class='p-1 text-hover-yellow'>About</a>
                <a href=""class='p-1 text-hover-cyan'>Work</a>
                <a href=""class='p-1 text-hover-green'>Contact</a>
            </div>
        </div>
    </nav>
    <div class="contains">

        <h2 class="mb-1">Colors</h2>
        <span class="text-primary">primary text</span> |
        <span class="text-secondary">secondary text</span> |
        <span class="text-error">error text</span> |
        <span class="text-info">info text</span> |
        <span class="text-blue">blue text</span> |
        <span class="text-red">red text</span> |
        <span class="text-green">green text</span> |
        <span class="text-yellow">yellow text</span> |
        <span class="text-purple">purple text</span> |
        <span class="text-orange">orange text</span> |
        <span class="text-gray">gray text</span> |
        <span class="text-pink">pink text</span> 

        <br><br>

        <span class="bg-primary text-white">bg primary</span> |
        <span class="bg-secondary text-white">bg secondary</span> |
        <span class="bg-error text-white">bg error</span> |
        <span class="bg-info text-white">bg info</span> |
        <span class="bg-blue text-white">bg blue</span> |
        <span class="bg-red text-white">bg red</span> |
        <span class="bg-green text-white">bg green</span> |
        <span class="bg-yellow text-white">bg yellow</span> |
        <span class="bg-purple text-white">bg purple</span> |
        <span class="bg-orange text-white">bg orange</span> |
        <span class="bg-gray text-white">bg gray</span> |

        <br><br>

        <span class="bg-primary-dark-8 text-white">bg primary dark 8</span> |
        <span class="bg-primary-dark-6 text-white">bg primary dark 6</span> |
        <span class="bg-primary-dark-4 text-white">bg primary dark 4</span> |
        <span class="bg-primary-dark-2 text-white">bg primary dark 2</span> |
        <span class="bg-primary text-white">primary</span> |
        <span class="bg-primary-light-2 text-white">bg primary light 2</span> |
        <span class="bg-primary-light-4 text-white">bg primary light 4</span> |
        <span class="bg-primary-light-6 text-white">bg primary light 6</span> |
        <span class="bg-primary-light-8 text-white">bg primary light 8</span> |

        <br><br>
        <a href="#" class="text-primary text-hover-red">hover me</a>
        <hr class="mt-1 mb-1">

        <!-- font sizes -->
        <h2 class="mb-1">Font Sizes</h2>
        <div class="f-sm">this is small font</div>
        <div class="f-md">this is medium font</div>
        <div class="f-lg">this is large font</div>
        <div class="f-xl">this is extra large font</div>
        <div class="f-xxl">this is extra, extra large font</div>

        <hr class="mt-1 mb-1">

        <!-- buttons -->
        <h2 class="mb-1">Buttons</h2>
        <button class="btn">default btn</button>
        <button class="btn-primary text-white br-full bc-black">click me</button>
        <button class="btn-secondary text-white">click me</button>
        <button class="btn-error text-white bc-green">click me</button>
        <button class="btn-info">click me</button>
        <button class="btn-outlined-purple text-purple text-hover-white">click me</button>
        <button class="btn-outlined-orange text-orange text-hover-white">click me</button>
        <button class="btn-complement-purple br-rounded">click me</button>
        <button class="btn-complement-primary">click me</button>

        <hr class="mt-1 mb-1">
        <!-- cards -->
        <h2 class="mb-1">Cards</h2>
        <div class="card">
            <h1 class="card-title">This is a title</h1>
            <p class="card-body">Lorem ipsum dolor sit, amet consectetur adipisicing elit. In sunt, quo totam aliquam
                praesentium ducimus tempore sapiente quia nulla optio? Lorem ipsum, dolor sit amet consectetur <a
                    href="">adipisicing elit</a>. Libero laboriosam laborum exercitationem autem commodi voluptas odio
                aliquid ut velit doloremque minima, quaerat dolores, corporis consequuntur totam nam id veniam maxime.
            </p>
        </div>

        <hr class="mt-1 mb-1">

        <!-- grid system -->
        <h2 class="mb-1">Grid System</h2>
        <div class="row gap-2 justify-center">
            <div class="col-12-xs col-5-sm col-3-xl">
                <div class="card">
                    <h3 class="card-title">Hello, Developers</h3>
                    <p class="card-body">Lorem ipsum, dolor sit amet consectetur adipisicing elit.</p>
                </div>
            </div>
            <div class="col-12-xs col-5-sm col-3-xl">
                <div class="card">
                    <h3 class="card-title">Hello, Developers</h3>
                    <p class="card-body">Lorem ipsum, dolor sit amet consectetur adipisicing elit.</p>
                </div>
            </div>
            <div class="col-12-xs col-5-sm col-3-xl">
                <div class="card">
                    <h3 class="card-title">Hello, Developers</h3>
                    <p class="card-body">Lorem ipsum, dolor sit amet consectetur adipisicing elit.</p>
                </div>
            </div>
            <div class="col-12-xs col-5-sm col-3-xl">
                <div class="card">
                    <h3 class="card-title">Hello, Developers</h3>
                    <p class="card-body">Lorem ipsum, dolor sit amet consectetur adipisicing elit.</p>
                </div>
            </div>
        </div>

        <hr class="mt-1 mb-1">

        <!-- utilities -->
        <h2>Using Utilities</h2>
        <div class="mt-2 text-orange-dark-2 bg-orange-light-5 p-1 br-sm">
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolores, perspiciatis!</p>
        </div>
        <div class="mt-2 text-secondary-dark-2 bg-secondary-light-5 p-1 br-lg bc-red">
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolores, perspiciatis!</p>
        </div>
        <div class="mt-2 text-gray bg-yellow p-1 br-rounded">
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolores, perspiciatis!</p>
        </div>
        <div class="d-i-b bg-purple text-white o-1 mt-3 mr-3 p-2">opacity 10</div>
        <div class="d-i-b bg-purple text-white o-3 mt-3 mr-3 p-2">opacity 30</div>
        <div class="d-b bg-purple text-white o-5 mt-3 mr-3 p-2">opacity 50</div>
        <div class="d-i-b bg-purple text-white o-7 mt-3 mr-3 p-2">opacity 70</div>
        <div class="d-i-b bg-purple text-white o-9 mt-3 mr-3 p-2">opacity 90</div>

        <hr class="mt-1 mb-1">

        <h1>Any Mistake feel free to say me. ❤Thanks</h1>

    </div>
