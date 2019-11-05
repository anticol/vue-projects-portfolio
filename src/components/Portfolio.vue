<template>

    <!--// HE AND SHE-->
    <div class='portfolio'>

        <div class='portfolio-item'>
            <h3>Free Time in Brno</h3>
            <div>
                <b-btn v-b-modal.modal01 variant="primary">
                    <img src='../assets/volnycasvbrne.jpg'/>
                </b-btn>
                <b-modal size="lg" id="modal01" title="Free Time in Brno"
                         ok-variant="primary" ok-title="Application"
                         @ok="openURL('https://www.data.brno.cz/volnycasvbrne')">
                    <p class="my-1">
                    <ul class="short_description">
                        <li><span class="li-header">When: </span> 10/2018 – 11/2019</li>
                        <li><span class="li-header">Type: </span> Master thesis</li>
                        <li><span class="li-header">Technologies: </span>HTML5, CSS3, JavaScript, Dojo, Arcade, Node.js,
                            PHP
                        </li>
                        <li><span class="li-header">My role: </span>Whole work (analysis, design, implementation,
                            testing, deployment, server customization, maintenance)
                        </li>
                    </ul>

                    <img src='../assets/volnycasvbrne.jpg'/>
                    </p>
                </b-modal>
            </div>
            <p>Web application mapping options of spending free time in Brno. It is a mashup application which collets
                open data from different sources and shows them on the map.

            </p>
        </div>


        <div class='portfolio-item'>
            <h3>He And She e-commerce</h3>
            <div>
                <b-btn v-b-modal.modal1 variant="primary">
                    <img src='../assets/heandshe-main.jpg'/>
                </b-btn>
                <b-modal size="lg" id="modal1" title="He And She e-commerce"
                         ok-variant="primary" ok-title="Application" @ok="openURL('https://www.heandshe.sk')">
                    <p class="my-1">
                    <ul class="short_description">
                        <li><span class="li-header">When: </span> 04/2019 – 07/2019</li>
                        <li><span class="li-header">Type: </span> Remote project at HE& SHE, s.r.o.</li>
                        <li><span class="li-header">Technologies: </span>HTML5, CSS3, JavaScript, jQuerry, Bootstrap,
                            PHP, MySQL, WooCommerce, WordPress, Superfaktura API (invoicing system), 24pay (payment
                            gateway)
                        </li>
                        <li><span class="li-header">My role: </span>Whole work (analysis, design, implementation,
                            testing, deployment, server customization, maintenance)
                        </li>
                    </ul>
                    Creating a responsive eshop selling clothes and fashion accessories. Eshop is using
                    Woocommerce. I was customizing template, plugins and UI. Integrating external systems for
                    invoicing, transportation and paying with credit cards. Writing own scripts for email
                    modifications and payment/transport restrictions. Making speed and performance optimizations.
                    Creating campaigns for promotion at Facebook and Instagram.
                    <img src='../assets/heandshe-main.jpg'/>
                    </p>
                </b-modal>
            </div>
            <p>Responsive eshop selling clothes and fashion accessories.</p>
        </div>

        <!--BMEDIC-->
        <div class='portfolio-item'>
            <h3>Bmedic</h3>
            <div>
                <b-btn v-b-modal.modal11 variant="primary">
                    <img src='../assets/bmedic-main.jpg'/>
                </b-btn>
                <b-modal size="lg" id="modal11" title="Bmedic"
                         ok-variant="primary" ok-title="Application" @ok="openURL('https://www.bmedic.cz')">
                    <p class="my-1">
                    <ul class="short_description">
                        <li><span class="li-header">When: </span> 02/2019 – 11/2019</li>
                        <li><span class="li-header">Type: </span> Remote projects at Bmedic education s.r.o.</li>
                        <li><span class="li-header">Technologies: </span>HTML5, CSS3, JavaScript, Bootstrap, PHP, MySQL,

                        <li><span class="li-header">My role: </span>Whole work (analysis, design, implementation,
                            testing, deployment, server customization, maintenance)
                        </li>
                    </ul>
                    Creating and modification of responsive websites providing courses tailored for students who
                    would like to study general medicine, dentistry, physiotherapy biology, chemistry and physics at
                    Masaryk University in
                    Czechia. Websites/Eshops are using WordPress as main CMS system. I was customizing templates,
                    plugins and UI. Integrating external systems for billing, currency changer. Writing own scripts
                    for translations, deposits, emails modifications, logging in using Google and Facebook. Making
                    speed and performance optimizations, etc,..
                    <br>
                    Three webpages were implemented:
                    <ul>
                        <li><a href="https://bmedic.cz/">Bmedic.cz</a></li>
                        <li><a href="https://bmedic.eu/">Bmedic.eu</a></li>
                        <li><a href="https://bmedic-online.cz/">Bmedic-online.cz</a></li>
                    </ul>
                    <a href="https://www.davidhorov.com/recommendationletters/lor-bmedic-education.pdf" target="_blank"
                       style="text-decoration: none">
                        <button type="button" class="btn btn-success">Recommendation letter from the CEO of Bmedic
                            education s.r.o.
                        </button>
                    </a>
                    <img src='../assets/bmedic-main.jpg'/>
                    </p>
                </b-modal>
            </div>
            <p>Responsive websites providing courses tailored for students who
                would like to study general medicine, dentistry, physiotherapy biology, chemistry and physics at Masaryk
                University in Czechia.</p>
        </div>

        <!--SMART QUIZ-->
        <div class='portfolio-item'>
            <h3>Smart Quiz</h3>
            <div>
                <b-btn v-b-modal.modal111 variant="primary">
                    <img src='../assets/smartquiz2.png'/>
                </b-btn>
                <b-modal size="lg" id="modal111" title="Smart Quiz"
                         ok-variant="primary" ok-title="Application"
                         @ok="openURL('https://www.bmedic-online.cz/testovani')">
                    <p class="my-1">
                    <ul class="short_description">
                        <li><span class="li-header">When: </span> 08/2018 - 11/2019</li>
                        <li><span class="li-header">Type: </span> Remote project at Bmedic education s.r.o.</li>
                        <li><span class="li-header">Technologies: </span>HTML5, CSS3, JavaScript, Bootstrap, PHP, SQL
                        </li>
                        <li><span class="li-header">My role: </span>Whole work (analysis, design, implementation,
                            testing, deployment, server customization, maintenance)
                        </li>
                    </ul>
                    TODO

                    <a href="https://www.davidhorov.com/recommendationletters/lor-bmedic-education.pdf" target="_blank"
                       style="text-decoration: none">
                        <button type="button" class="btn btn-success">Recommendation letter from the CEO of Bmedic
                            education s.r.o.
                        </button>
                    </a>

                    <img src='../assets/smartquiz2.png'/>
                    <img src='../assets/smartquiz1.png'/>
                    <img src='../assets/smartquiz3.png'/>
                    <img src='../assets/smartquiz4.png'/>

                    </p>
                </b-modal>
            </div>
            <p>TODO</p>
        </div>

        <!--RESPONSIVE EMAILS-->
        <div class='portfolio-item'>
            <h3>Responsive email templates</h3>
            <div>
                <b-btn v-b-modal.modal19 variant="primary">
                    <img src='../assets/emails-main.jpg'/>
                </b-btn>
                <b-modal size="lg" id="modal19" title="Responsive email templates">
                    <p class="my-1">
                    <ul class="short_description">
                        <li><span class="li-header">When: </span> 2019</li>
                        <li><span class="li-header">Type: </span> Remote project at Houssam All (Upwork)</li>
                        <li><span class="li-header">Technologies: </span>HTML5, CSS3, Vue.js, Bootstrap</li>
                        <li><span class="li-header">My role: </span>Front-end developer</li>
                    </ul>
                    TODO
                    <a href="https://www.davidhorov.com/recommendationletters/lor-houssam-all.pdf" target="_blank"
                       style="text-decoration: none">
                        <button type="button" class="btn btn-success">Recommendation letter from Houssam All (project
                            manager)
                        </button>
                    </a>
                    <img src='../assets/emails-main.jpg'/>
                    </p>
                </b-modal>
            </div>
            <p>Implementing responsive emails from PSD template.</p>
        </div>

        <!--RIESIME FINANCIE-->
        <div class='portfolio-item'>
            <h3>RiesimeFinancie.sk</h3>
            <div>
                <b-btn v-b-modal.modal22 variant="primary">
                    <img src='../assets/riesimefinancie-main.jpg'/>
                </b-btn>
                <b-modal size="lg" id="modal22" title="Riešime Financie"
                         ok-variant="primary" ok-title="Application" @ok="openURL('https://www.riesimefinancie.sk')">
                    <p class="my-1">
                    <ul class="short_description">
                        <li><span class="li-header">When: </span> 09/2018 - 12/2018</li>
                        <li><span class="li-header">Type: </span> Remote project for local entrepreneur</li>
                        <li><span class="li-header">Technologies: </span>HTML5, CSS3, JavaScript, Bootstrap, PHP, MySQL,
                            WordPress
                        </li>
                        <li><span class="li-header">My role: </span>Whole work (analysis, design, implementation,
                            testing, deployment, server customization, maintenance)
                        </li>
                    </ul>
                    Creating responsive company website providing insurance and investment services. Website is
                    using WordPress as main CMS system. During several meetings we have created an idea for this
                    website from scratch. We defined features, which were implemented and regularly discussed.
                    <img src='../assets/riesimefinancie-main.jpg'/>
                    </p>
                </b-modal>
            </div>
            <p>Responsive company website providing insurance and investment services.</p>
        </div>

        <!--IBS SECURITY-->
        <div class='portfolio-item'>
            <h3>IBS Security</h3>
            <div>
                <b-btn v-b-modal.modal3 variant="primary">
                    <img src='../assets/ibs-main.jpg'/>
                </b-btn>
                <b-modal size="lg" id="modal3" title="IBS Security"
                         ok-variant="primary" ok-title="Application" @ok="openURL('https://www.ibs-security.sk')">
                    <p class="my-1">
                    <ul class="short_description">
                        <li><span class="li-header">When: </span>01/2019 - 02/2019</li>
                        <li><span class="li-header">Type: </span> Remote project at Nefkus</li>
                        <li><span class="li-header">Technologies: </span>HTML5, CSS3, JavaScript, Bootstrap, PHP, MySQL,
                            WordPress
                        </li>
                        <li><span class="li-header">My role: </span>Implementation, testing, deployment</li>
                    </ul>
                    Creating responsive company website providing security services. Website is using WordPress as main
                    CMS system. I was transferring PSD inputs into template, customizing plugins and UI, editing images
                    and making speed and performance optimizations, etc,..
                    <img src='../assets/ibs-main.jpg'/>
                    </p>
                </b-modal>
            </div>
            <p>Responsive company website providing security services.</p>
        </div>

        <!--DavidHorov-->
        <div class='portfolio-item'>
            <h3>DavidHorov.com</h3>
            <div>
                <b-btn v-b-modal.modal44 variant="primary">
                    <img src='../assets/davidhorov_responsive.jpg'/>
                </b-btn>
                <b-modal size="lg" id="modal44" title="DavidHorov.com"
                         ok-variant="primary" ok-title="Source Code"
                         @ok="openURL('TODO')">
                    <p class="my-1">
                    <ul class="short_description">
                        <li><span class="li-header">When: </span> 01/2019 – 02/2019</li>
                        <li><span class="li-header">Type: </span> Remote work for myself
                        </li>
                        <li><span class="li-header">Technologies: </span> Vue.js, HTML5, CSS3, Bootstrap, Javascript
                        </li>
                        <li><span class="li-header">My role: </span>Front-end developer</li>
                    </ul>
                    Responsive personal portfolio webpage
                    <img src='../assets/davidhorov_responsive.jpg'/>
                    </p>
                </b-modal>
            </div>
            <p>Responsive personal portfolio webpage </p>
        </div>

        <!--NOVELTY-->
        <div class='portfolio-item'>
            <h3>Novelty</h3>
            <div>
                <b-btn v-b-modal.modal4 variant="primary">
                    <img src='../assets/novelty-main.png'/>
                </b-btn>
                <b-modal size="lg" id="modal4" title="Novelty"
                         ok-variant="primary" ok-title="Source Code"
                         @ok="openURL('https://github.com/anticol/Novelty-IBM-cloud-project')">
                    <p class="my-1">
                    <ul class="short_description">
                        <li><span class="li-header">When: </span> 04/2019 – 06/2019</li>
                        <li><span class="li-header">Type: </span> University project for the course – Services –
                            Systems, Modeling, Execution (PA181)
                        </li>
                        <li><span class="li-header">Technologies: </span> React, IBM Cloud (IBM Kubernetes, IBM
                            Container Registry and IBM Watson), HTML5, CSS3, Bootstrap, BBC/CNN API
                        </li>
                        <li><span class="li-header">My role: </span>Application Designer, Front-end developer</li>
                    </ul>
                    Project Novelty aims to create the news application for people with impaired vision and hearing,
                    and to provide the integration into the application as a service. The concept of voice
                    synthesizing is being progressively more used, but there is no application what would allow the
                    news websites to have their source customized and integrated into the single app that will be
                    used by people with vision impairment. With use of the IBM technologies, we are able to create a
                    scalable solution for news integration, while building a single app that will contain all the
                    news sources and will be used by the end-users.
                    <img src='../assets/novelty_award.png'/>
                    <img src='../assets/novelty-main.png'/>
                    <img src='../assets/novelty-2.png'/>

                    </p>
                </b-modal>
            </div>
            <p>Web applications Novelty aims to create the news application for people with impaired vision and hearing,
                and to provide the integration into the Application As A Service. </p>
        </div>

        <!--ANIMEFEST-->
        <div class='portfolio-item'>
            <h3>Animefest panel</h3>
            <div>
                <b-btn v-b-modal.modal5 variant="primary">
                    <img src='../assets/animefest-main.png'/>
                </b-btn>
                <b-modal size="lg" id="modal5" title="Animefest panel"
                         ok-variant="primary" ok-title="Source Code"
                         @ok="openURL('https://github.com/anticol/festival_panel')">
                    <p class="my-1">
                    <ul class="short_description">
                        <li><span class="li-header">When: </span> 02/2017 – 06/2017</li>
                        <li><span class="li-header">Type: </span> University project for the course – Modern Markup
                            Languages and Their Applications Star (PB138)
                        </li>
                        <li><span class="li-header">Technologies: </span> JavaScript, jQuery, XML, HTML, CSS, Firebase,
                            Materialize
                        </li>
                        <li><span class="li-header">My role: </span>Project manager, Application Designer, Front-end
                            developer
                        </li>
                    </ul>
                    The task of this university group project was to create an information screen and administration
                    panel for the festival Animefest.cz. It contains multiple features such as displaying the
                    current program from XML data, fetching images from Instagram with a specified hashtag, fully
                    operational and responsive administration interface, showing static pages, iframes, news ticker.
                    Application works on the basic of showing / hiding scenes based on the configuration file.
                    Displaying
                    news, Instagram posts and static pages work in cooperation with administration panel.
                    <img src='../assets/animefest-main.png'/>
                    </p>
                </b-modal>
            </div>
            <p>Web application consisting of information screen and administration panel for the festival
                Animefest.cz.</p>
        </div>

        <!--SOURCE CODE INSPECTOR-->
        <div class='portfolio-item'>
            <h3>Source Code Inspector</h3>
            <div>
                <b-btn v-b-modal.modal6 variant="primary">
                    <img src='../assets/scinspection-main.png'/>
                </b-btn>
                <b-modal size="lg" id="modal6" title="Source Code Inspector"
                         cancel-variant="secondary" cancel-title="Thesis"
                         @cancel="openURL('https://is.muni.cz/auth/th/lrs0e')"
                         ok-variant="primary" ok-title="Source Code"
                         @ok="openURL('https://github.com/anticol/scinspector')">
                    <p class="my-1">
                    <ul class="short_description">
                        <li><span class="li-header">When: </span> 10/2016 – 06/2017</li>
                        <li><span class="li-header">Type: </span> Bachelor thesis (OpenSource)</li>
                        <li><span class="li-header">Technologies: </span> C, C++, Bash, Go</li>
                        <li><span class="li-header">My role: </span>Whole work (analysis, design, implementation,
                            testing, deyployment)
                        </li>
                    </ul>
                    Teachers of programming courses form their opinions about students mistakes based on their
                    previous experience. This work qualitatively examines the programming problems in form of
                    interviews with teachers and tries to verify or refute their hypotheses based on real data from
                    source codes. Comparing real mistakes and rebellions of teachers offers an objective view of
                    programming errors and good practice breaches. The output is automated bash script for searching
                    for specified errors. The aim of this work is to analyze acquired data and on the basis of total
                    data improve the quality of course PB071 - Principles of low-level programming and PB161 - C++
                    programming (Courses at Faculty of Informatics Masaryk University in Brno)
                    <img src='../assets/scinspection-main.png'/>
                    <img src='../assets/sc-inspector2.png'/>

                    </p>
                </b-modal>
            </div>
            <p>Command line automated bash script which searchers for specific errors and programming mistakes in C/C++
                source codes.</p>
        </div>

        <!--MARKIZA-->
        <div class='portfolio-item'>
            <h3>Markiza for HbbTV</h3>
            <div>
                <b-btn v-b-modal.modal7 variant="primary">
                    <img src='../assets/markiza-main.png'/>
                </b-btn>
                <b-modal size="lg" id="modal7" title="Markiza for HbbTV"
                         ok-variant="primary" ok-title="More Information"
                         @ok="openURL('https://www.mautilus.com/projects/detail/markiza/')">

                    <p class="my-1">
                    <ul class="short_description">
                        <li><span class="li-header">When: </span> 2016/2017</li>
                        <li><span class="li-header">Type: </span> On-site project at Mautilus</li>
                        <li><span class="li-header">Technologies: </span> React, HTML5, CSS3, jQuerry</li>
                        <li><span class="li-header">My role: </span>Front-end developer</li>
                    </ul>
                    TV Markíza is the most popular privately held television in Slovakia owned by CME. We have
                    developed and launched the first HbbTV application.
                    When the application was launched, it allowed the viewers to watch news from the server
                    www.tvnoviny.sk, weather information and teletext, while in the latest update the list of
                    applications was extended by video archive, EPG and several HbbTV games to give the audience
                    more entertainment and information.
                    <img src='../assets/markiza-main.png'/>
                    <img src='../assets/markiza-2.png'/>
                    <img src='../assets/markiza-3.png'/>
                    </p>
                </b-modal>
            </div>
            <p>HbbTV application for the most popular commercial TV in Slovakia. Displays news, weather information,
                teletext and contains video archive and interactive games. </p>
        </div>

        <!--YOUSEE-->
        <div class='portfolio-item'>
            <h3>YouSee</h3>
            <div>
                <b-btn v-b-modal.modal8 variant="primary">
                    <img src='../assets/yousee-main.png'/>
                </b-btn>
                <b-modal size="lg" id="modal8" title="YouSee"
                         ok-variant="primary" ok-title="More Information"
                         @ok="openURL('https://www.mautilus.com/projects/detail/yousee/')">

                    <p class="my-1">
                    <ul class="short_description">
                        <li><span class="li-header">When: </span> 2016/2017</li>
                        <li><span class="li-header">Type: </span> On-site project at Mautilus</li>
                        <li><span class="li-header">Technologies: </span> React, HTML5, CSS3, SQL</li>
                        <li><span class="li-header">My role: </span>Front-end developer, API analyst</li>
                    </ul>

                    YouSee is the largest quadruple play service provider in Denmark and is a subsidiary of TDC
                    Group. YouSee currently has 1.1 million customers in Denmark.
                    We at Mautilus have developed and deployed for youSee an application for Samsung and LG TV
                    platforms using our Smart TV SDK. It is one of our long-term ongoing project, with a unique
                    application port from ST.
                    During the development we've used the newest technology/libraries for ReactJS, in combination
                    with our previously mentioned SDK 3.0.
                    TDC Group is the largest telecommunications company in Denmark. TDC Group is the parent company
                    of several subsidiaries and brands such as: Blockbuster, Dansk Kabel TV, Fullrate, Get AS,
                    NetDesign, TDC Erhverv, Telmore and YouSee.
                    <img src='../assets/yousee-main.png'/>
                    </p>
                </b-modal>
            </div>
            <p>Application for Samsung and LG TV platforms. YouSee is the largest quadruple play service provider in
                Denmark. The features and functionality of this app is similar to Netflix</p>
        </div>

        <!--O2 TV SPORT-->
        <div class='portfolio-item'>
            <h3>O2 TV Sport</h3>
            <div>
                <b-btn v-b-modal.modal9 variant="primary">
                    <img src='../assets/o2-main.png'/>
                </b-btn>
                <b-modal size="lg" id="modal9" title="O2 TV Sport"
                         ok-variant="primary" ok-title="More Information"
                         @ok="openURL('https://www.mautilus.com/projects/detail/o2-tv-sport')">
                    <p class="my-1">
                    <ul class="short_description">
                        <li><span class="li-header">When: </span> 2016/2017</li>
                        <li><span class="li-header">Type: </span> On-site project at Mautilus</li>
                        <li><span class="li-header">Technologies: </span> HTML5, CSS3, JavaScript, jQuery</li>
                        <li><span class="li-header">My role: </span>Front-end developer</li>
                    </ul>
                    One of the first HbbTV applications in the world using the SMS payment gateway to allow access to a
                    premium content.
                    The application has been developed for O2 Czech Republic.
                    The HbbTV application runs on the free-to-air O2 TV Sport channel and allows users to directly
                    purchase the access to its premium content through SMS payment gateway from their mobile phones
                    within a few seconds.
                    In addition to that, users can also access the VOD archive, as they can use a start-over feature and
                    go through the catch-up content that is available for up to 50 hours backwards.
                    The application also includes the archive of free content produced by O2 TV.
                    <br>
                    <img src='../assets/o2-main.png'/>
                    <img src='../assets/o2-2.png'/>
                    <img src='../assets/o2-3.png'/>
                    <img src='../assets/o2-4.png'/>
                    </p>
                </b-modal>
            </div>
            <p>One of the first HbbTV applications in the world using the SMS payment gateway to allow access to a
                premium content. Users can access the VOD archive, archive of free content produced by O2 TV and premium
                content (live streams).

            </p>
        </div>


    </div>
</template>

<script>
    export default {
        name: 'Portfolio',
        data() {
            return {
                items: [
                    {
                        name: 'He and She e-commerce',
                        img_src: '../assets/heandshe-main.jpg',
                        description: 'sadasdasd',
                        app: 'https://www.ibs-security.sk',
                        git: 'https://www.ibs-security.sk/hovno',
                    },
                    {
                        name: 'asdasd commerce',
                        img_src: '../assets/heandshe-main.jpg',
                        description: 'A proof-of-concept site for a pet adoption organization. Built using Mongoose, Express, React and Node (MERN stack).',
                        app: 'https://www.ibs-security.sk',
                        git: 'https://www.ibs-security.sk/hovno',
                    }
                ]
            }
        },
        methods: {
            openURL(arg) {
                window.open(arg);
            }
        }
    }

</script>
<style scoped>
    b-btn > img:hover {
        cursor: pointer;
    }

    .portfolio {
        width: 75%;
        margin: 0 auto;
        display: flex;
        flex-wrap: wrap;
        align-items: center;
        justify-content: center;
    }

    .portfolio-item {
        width: 50%;
        min-width: 350px;
        max-width: 400px;
        height: 420px;
        display: flex;
        flex-direction: column;
        align-items: center;
        text-align: justify;
        margin: 20px;
        box-shadow: 0 0 30px 0 #343a40;
        padding: 20px;
        border-radius: 15px;
    }

    .portfolio-item img {
        max-width: 100%;
        display: block;
    }

    .portfolio-item h3 {
        font-family: Cambria;
    }

    img {
        max-width: 100%
    }

    .li-header {
        font-weight: bold;
    }

    .short_description {
        padding: 0;
        list-style-type: none;
    }

    .my-1 > img {
        margin: 0 auto;
        margin-top: 10px;
        max-width: 85%;
        display: block;
    }

    .portfolio-item > h3 {
        margin-bottom: 20px;
    }

    .btn-success {
        margin-right: auto;
        margin-left: auto;
        margin-top: 15px;
        margin-bottom: 25px;
        display: block;
    }
</style>
