<template>
    <div class="services-area bg-right-shape ptb-100">
        <div class="container-fluid">
            <div class="row align-items-center">
                <div class="services-content it-service-content">
                    <div class="content left-content">
                        <div class="icon">
                            <img src="../../assets/img/icon1.png" alt="image">
                        </div>
                        <h2>Web & Mobile Development</h2>
                        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris.</p>

                        <div class="row">
                            <div class="col-sm-6">
                                <div class="feature-box">
                                    <i class='bx bxs-badge-check'></i>  
                                    Responsive Design
                                </div>
                            </div>
                            <div class="col-sm-6">
                                <div class="feature-box">
                                    <i class='bx bxs-badge-check'></i> 
                                    UI / UX Design
                                </div>
                            </div>
                            <div class="col-sm-6">
                                <div class="feature-box">
                                    <i class='bx bxs-badge-check'></i> 
                                    Mobile App Development
                                </div>
                            </div>
                            <div class="col-sm-6">
                                <div class="feature-box">
                                    <i class='bx bxs-badge-check'></i> 
                                    Laravel Web Development
                                </div>
                            </div>
                            <div class="col-sm-6">
                                <div class="feature-box">
                                    <i class='bx bxs-badge-check'></i> 
                                    React Web Development
                                </div>
                            </div>
                            <div class="col-sm-6">
                                <div class="feature-box">
                                    <i class='bx bxs-badge-check'></i> 
                                    Angular Web Development
                                </div>
                            </div>
                        </div>

                        <router-link to="/single-service" class="default-btn">
                            <i class="bx bxs-spreadsheet"></i> 
                            Learn More 
                            <span></span>
                        </router-link>
                    </div>
                </div>

                <div class="services-image">
                    <div class="image">
                        <img src="../../assets/img/services-image/service1.png" alt="image">
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'MobileDevelopment'
}
</script>