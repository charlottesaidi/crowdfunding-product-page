<template>
    <div class="modal" id="modal1">
        <div id="modal-selected" class="modal-content">
            <div class="row modal_main_title">
                <div class="col s11">
                    <h3 class="black-text">Back this project</h3>
                </div>
                <div class="col s1 right-align">
                    <img src="../assets/images/icon-close-modal.svg" alt="" class="modal-action modal-close">
                </div>
            </div>
            <p>Want to support us in bringing Mastercraft Bamboo Monitor Riser out in the world?</p>

            <div class="sub-section" id="sub_section_0">
                <div class="container">
                    <div class="row">
                        <p class="black-pledge">
                            <label>
                                <input data-target="sub_section_0" class="with-gap" name="group0" type="radio"  />
                                <span class="black-text title">Pledge with no reward</span>
                            </label>
                        </p>
                    </div>
                    <p class="text">Choose to support us without a reward if you simply believe in our project. As a backer, you will be signed up to receive product updates via email.</p>
                </div>
            </div>

            <div class="sub-section" id="sub_section_1">
                <div class="container">
                    <div class="row">
                        <p class="black-pledge col s12 l9">
                            <label>
                                <input data-target="sub_section_1" class="with-gap col s12 m8" name="group0" type="radio"  />
                                <span class="selected-choice" data-target="pledge_0">
                                    <span class="black-text hide-on-med-and-down">
                                        <span class="title">Bamboo Stand</span>
                                        <span class="pledge">Pledge $25 or more</span>
                                    </span>
                                    <span class="black-text hide-on-large-only">
                                        <span class="title">Bamboo Stand</span> <br>
                                        <span class="pledge">Pledge $25 or more</span>
                                    </span>
                                </span>
                            </label>
                        </p>
                        <p class="col s12 l3 right-align hide-on-med-and-down"><span class="left-black-text">101</span> left</p>
                    </div>
                    <p class="text">You get an ergonomic stand made of natural bamboo. You've helped us launch our promotional campaign, and you’ll be added to a special Backer member list.</p>
                    <p class="hide-on-large-only"><span class="left-black-text">101</span> left</p>
                </div>
                <div id="pledge_0" class="hidden pledge-selected">
                    <div class="container vw-pledge valign-wrapper">
                        <div class="label">
                            <p>Enter your pledge</p>
                        </div>
                        <div class="form_group valign-wrapper">
                            <label>
                                <span class="num_label grey-text">$</span>
                                <input type="number" name="pledge_0" min="25" value="25">
                            </label>
                            <input type="submit" class="btn-small custom-btn submitted" value="Continue">
                        </div>
                    </div>
                </div>
            </div>

            <div class="sub-section" id="sub_section_2">
                <div class="container">
                    <div class="row">
                        <p class="black-pledge col s12 l9">
                            <label>
                                <input data-target="sub_section_2" class="with-gap col s12 m8" name="group0" type="radio"  />
                                <span class="selected-choice" data-target="pledge_1">
                                    <span class="black-text hide-on-med-and-down">
                                        <span class="title">Black Edition Stand</span>
                                        <span class="pledge">Pledge $75 or more</span>
                                    </span>
                                    <span class="black-text hide-on-large-only">
                                        <span class="title">Black Edition Stand</span> <br>
                                        <span class="pledge">Pledge $75 or more</span>
                                    </span>
                                </span>
                            </label>
                        </p>
                        <p class="col s12 l3 right-align hide-on-med-and-down"><span class="left-black-text">64</span> left</p>
                    </div>
                    <p class="text">You get a Black Special Edition computer stand and a personal thank you. You’ll be added to our Backer member list. Shipping is included.</p>
                    <p class="hide-on-large-only"><span class="left-black-text">64</span> left</p>
                </div>
                <div id="pledge_1" class="hidden pledge-selected">
                    <div class="container vw-pledge valign-wrapper">
                        <div class="label">
                            <label>Enter your pledge</label>
                        </div>
                        <div class="form_group valign-wrapper">
                            <input type="number" name="pledge_1" placeholder="75" min="75">
                            <input type="submit" class="btn-small custom-btn submitted" value="Continue">
                        </div>
                    </div>
                </div>
            </div>

            <div class="sub-section out" id="sub_section_3">
                <div class="container">
                    <div class="row">
                        <p class="black-pledge col s12 l9">
                            <label>
                                <input data-target="sub_section_3" class="with-gap col s12 m8" name="group0" type="radio"  />
                                <span class="selected-choice" data-target="pledge_2">
                                    <span class="black-text hide-on-med-and-down">
                                        <span class="title">Mahogany Special Edition</span>
                                        <span class="pledge">Pledge $200 or more</span>
                                    </span>
                                    <span class="black-text hide-on-large-only">
                                        <span class="title">Mahogany Special Edition</span> <br>
                                        <span class="pledge">Pledge $200 or more</span>
                                    </span>
                                </span>
                            </label>
                        </p>
                        <p class="col s12 l3 right-align hide-on-med-and-down"><span class="left-black-text">0</span> left</p>
                    </div>
                    <p class="text">You get two Special Edition Mahogany stands, a Backer T-Shirt, and a personal thank you. You’ll be added to our Backer member list. Shipping is included.</p>
                    <p class="hide-on-large-only"><span class="left-black-text">0</span> left</p>
                </div>
                <div id="pledge_2" class="hidden pledge-selected">
                    <div class="container vw-pledge valign-wrapper">
                        <div class="label">
                            <label>Enter your pledge</label>
                        </div>
                        <div class="form_group valign-wrapper">
                            <input type="number" name="pledge_2" placeholder="200" min="200">
                            <input type="submit" class="btn-small custom-btn submitted" value="Continue">
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <div id="modal-completed" class="hidden center-align">
            <div class="container">
                <a class="btn-floating btn-large">
                <i class="large material-icons">check</i>
            </a>
            <h2 class="black-text">Thanks for your support!</h2>
            <p>Your pledge brings us one step closer to sharing Mastercraft Bamboo Monitor Riser worldwide. You will get an email once our campaign is completed.</p>
            <button class="btn-small custom-btn modal-action modal-close" id="got_it">Got it!</button>
            </div>
        </div>
    </div>
</template>

<script>
/* eslint-env jquery */
export default {
    mounted() {
        $(document).ready(function() {
            $('.modal').modal();

            $('.with-gap').click(function() {
                var section = $('#'+$(this).attr('data-target'));
                var sections = $('.modal .sub-section');
                sections.each(function () {
                    if($('.modal .sub-section').hasClass('active')) {
                        $('.modal .sub-section').removeClass('active');
                    }
                    section.addClass('active');
                });
            });

            $('.selected-choice').click(function() {
                $('.pledge-selected').each(function () {
                    if($('.pledge-selected').css('display', 'block')) {
                        $('.pledge-selected').hide();
                    }
                });
                    $('#'+$(this).attr('data-target')).slideToggle('slow');
            });

            $('.submitted').click(function() {
                $('#modal-selected').fadeOut();
                $('#modal-completed').fadeIn();
                $('#bookmarked').addClass('active');
                $('#bookmarked-text').text("Bookmarked");
            });

            $('#got_it').click(function() {
                $('#modal-selected').fadeIn();
                $('#modal-completed').fadeOut();
            });
        });
    }
}
</script>