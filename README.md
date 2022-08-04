# qb-racing-app-reskin
qb-phone-np-racing-app

OBS I USE LLBOOYAS QB-PHONE RESKIN, THIS MIGHT NOT FIT PERFECTLY FOR YOUR PHONE
https://github.com/llbooya/qb-phone-npstyle

![main menu](https://i.imgur.com/5XL0hIr.png)
![create race](https://i.imgur.com/GkW3vO7.png)
![leaderboard](https://i.imgur.com/YI3lQBp.png)
![leaderboard-2](https://i.imgur.com/FsQUwLz.png)
![create track](https://i.imgur.com/Gd1LOY3.png)

[install]
1. change ur css and js with these in your qb-phone
2. replace the racing app html with this 
                    <div class="racing-app">
                        <div class="racing-overview">
                            <div class="racing-app-header">
                            </div>

                            <div class="racing-races">
                            </div>

                            <div class="racing-buttons">
                                <div class="racing-button" id="setup-race">
                                    <i class="fas fa-flag-checkered"></i>
                                </div>
                                <div class="racing-button" id="leaderboards-race">
                                    <i class="fas fa-trophy"></i>
                                </div>
                                <div class="racing-button" id="create-race">
                                    <i class="fas fa-plus"></i>
                                </div>
                            </div>

                        </div>
                        <div class="racing-app-background">
                        </div>
                        <div class="racing-setup">
                            <div class="racing-app-header">
                                Racing - Setup
                            </div>

                            <span id="racing-setup-trackheader">Race Track</span>
                            <div class="dropdown">
                                <div class="select">
                                  <span>Select a Track</span>
                                  <i class="fa fa-chevron-left"></i>
                                </div>
                                <input type="hidden" name="gender">
                                <ul class="dropdown-menu"></ul>
                            </div>

                            <span id="racing-setup-lapsheader">Laps</span>
                            <input type="number" min="0" oninput="this.value = Math.abs(this.value)" class="racing-setup-laps" required spellcheck="false" placeholder="Number of laps (0 is Sprint)">

                            <span id="racing-setup-informationheader">Race Information</span>
                            <div class="racing-setup-information-distance">Select a Track</div>
                            <div class="racing-setup-information-creator">Select a Track</div>
                            <div class="racing-setup-information-wr">Select a Track</div>

                            <div class="racing-setup-buttons">
                                <div class="racing-setup-button" id="setup-race-accept" data-toggle="race-setup" data-placement="bottom" title="Accept">
                                    <i>SUBMIT</i>
                                </div>
                                <div class="racing-setup-button" id="setup-race-cancel" data-toggle="race-setup" data-placement="bottom" title="Cancel">
                                    <i>CANCEL</i>
                                </div>
                            </div>
                        </div>

                        <div class="racing-create">
                            <div class="racing-create-block">
                                <span id="racing-create-tracknameheader">Track Name</span>
                                <input type="text" class="racing-create-trackname" required spellcheck="false" placeholder="Name of your track">

                                <div class="racing-create-buttons">
                                    <div class="racing-create-button" id="racing-create-accept">
                                        <i>ACCEPT</i>
                                    </div>
                                    <div class="racing-create-button" id="racing-create-cancel">
                                        <i>DECLINE</i>
                                    </div>
                                </div>
                            </div>
                        </div>

                        <div class="phone-new-box-body" id="create-race-app-new">
                            <div class="phone-new-box-main">
                                <input class="phone-new-input-class" id="racing-create-trackname" type="text" placeholder="Name of your track">
                                <p> </p>
                                <div class="phone-new-box-btn box-new-red" id="box-new-cancel">Cancel</div>
                                <div class="phone-new-box-btn box-new-green" id="racing-create-accept">Submit</div>
                            </div>
                        </div>

                        <div class="racing-leaderboard">
                            <div class="racing-app-header">
                            </div>

                            <span id="racing-leaderboards-header">Leaderboard - Last Tracks</span>
                            <div class="racing-leaderboards">
                            </div>

                            <div class="racing-leaderboard-details">
                                <div class="racing-leaderboard-details-block">
                                    <div class="racing-leaderboard-details-back"><i class="fas fa-times-circle"></i></div>
                                    <div class="racing-leaderboard-details-block-trackname"><i class="fas fa-flag-checkered"></i> Prison</div>
                                    <span id="leaderboard-list-header"><span style="float: left;">Racer</span><span style="margin-left: 5.55vh;"><i class="fas fa-stopwatch"></i></span><span style="float: right; margin-right: 2vh;">#</span></span>
                                    <div class="racing-leaderboard-details-block-list">
                                    </div>
                                </div>
                            </div>

                            <div class="racing-leaderboards-button">
                                <i class="fas fa-times-circle"></i>
                            </div>
                        </div>
                    </div>
