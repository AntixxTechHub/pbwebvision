<template>
    <div class="services-area bg-left-color bg-left-shape bg-f4f6fc ptb-100">
        <div class="container-fluid">
            <div class="row align-items-center">
                <div class="services-image">
                    <div class="image">
                        <img src="../../assets/img/services-image/service2.png" alt="image">
                    </div>
                </div>

                <div class="services-content it-service-content">
                    <div class="content">
                        <div class="icon">
                            <img src="../../assets/img/icon1.png" alt="image">
                        </div>
                        <h2>Cloud Hosting Services</h2>
                        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris.</p>

                        <div class="row">
                            <div class="col-sm-6">
                                <div class="feature-box">
                                    <i class='bx bxs-badge-check'></i>  
                                    Cloud Databases
                                </div>
                            </div>
                            <div class="col-sm-6">
                                <div class="feature-box">
                                    <i class='bx bxs-badge-check'></i> 
                                    Hybrid Cloud
                                </div>
                            </div>
                            <div class="col-sm-6">
                                <div class="feature-box">
                                    <i class='bx bxs-badge-check'></i> 
                                    Email Servers
                                </div>
                            </div>
                            <div class="col-sm-6">
                                <div class="feature-box">
                                    <i class='bx bxs-badge-check'></i> 
                                    Website Hosting
                                </div>
                            </div>
                            <div class="col-sm-6">
                                <div class="feature-box">
                                    <i class='bx bxs-badge-check'></i> 
                                    File Storage
                                </div>
                            </div>
                            <div class="col-sm-6">
                                <div class="feature-box">
                                    <i class='bx bxs-badge-check'></i> 
                                    Backup Systems
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
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'HostingServices'
}
</script>