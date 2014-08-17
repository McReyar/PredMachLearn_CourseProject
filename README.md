



<!DOCTYPE html>
<html lang="en" class="   ">
  <head prefix="og: http://ogp.me/ns# fb: http://ogp.me/ns/fb# object: http://ogp.me/ns/object# article: http://ogp.me/ns/article# profile: http://ogp.me/ns/profile#">
    <meta charset='utf-8'>
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta http-equiv="Content-Language" content="en">
    
    
    <title>PredMachLearn_CourseProject/README.md at gh-pages · McReyar/PredMachLearn_CourseProject</title>
    <link rel="search" type="application/opensearchdescription+xml" href="/opensearch.xml" title="GitHub">
    <link rel="fluid-icon" href="https://github.com/fluidicon.png" title="GitHub">
    <link rel="apple-touch-icon" sizes="57x57" href="/apple-touch-icon-114.png">
    <link rel="apple-touch-icon" sizes="114x114" href="/apple-touch-icon-114.png">
    <link rel="apple-touch-icon" sizes="72x72" href="/apple-touch-icon-144.png">
    <link rel="apple-touch-icon" sizes="144x144" href="/apple-touch-icon-144.png">
    <meta property="fb:app_id" content="1401488693436528">

      <meta content="@github" name="twitter:site" /><meta content="summary" name="twitter:card" /><meta content="McReyar/PredMachLearn_CourseProject" name="twitter:title" /><meta content="PredMachLearn_CourseProject - Prediction Assignment Writeup" name="twitter:description" /><meta content="https://avatars1.githubusercontent.com/u/7771891?v=2&amp;s=400" name="twitter:image:src" />
<meta content="GitHub" property="og:site_name" /><meta content="object" property="og:type" /><meta content="https://avatars1.githubusercontent.com/u/7771891?v=2&amp;s=400" property="og:image" /><meta content="McReyar/PredMachLearn_CourseProject" property="og:title" /><meta content="https://github.com/McReyar/PredMachLearn_CourseProject" property="og:url" /><meta content="PredMachLearn_CourseProject - Prediction Assignment Writeup" property="og:description" />

    <link rel="assets" href="https://assets-cdn.github.com/">
    <link rel="conduit-xhr" href="https://ghconduit.com:25035">
    <link rel="xhr-socket" href="/_sockets">

    <meta name="msapplication-TileImage" content="/windows-tile.png">
    <meta name="msapplication-TileColor" content="#ffffff">
    <meta name="selected-link" value="repo_source" data-pjax-transient>
      <meta name="google-analytics" content="UA-3769691-2">

    <meta content="collector.githubapp.com" name="octolytics-host" /><meta content="collector-cdn.github.com" name="octolytics-script-host" /><meta content="github" name="octolytics-app-id" /><meta content="C2D0B3C6:0874:12970858:53F0A40D" name="octolytics-dimension-request_id" /><meta content="7771891" name="octolytics-actor-id" /><meta content="McReyar" name="octolytics-actor-login" /><meta content="9fbc5c644a8dc3d631e51245be77a8c69f334445e8d7f1064f961690ac8a1a54" name="octolytics-actor-hash" />
    

    
    
    <link rel="icon" type="image/x-icon" href="https://assets-cdn.github.com/favicon.ico">


    <meta content="authenticity_token" name="csrf-param" />
<meta content="UW8jZCHeU87Bxm8htp/+DkxZaAn8nYA95j4c83615uz8jzG0l8JJWqz1XN0mahqIvMjsWNeY2vqp6M8MAvXTQg==" name="csrf-token" />

    <link href="https://assets-cdn.github.com/assets/github-5efa7b0b8a55ddcee56e5aee3fa56109d1d2781c.css" media="all" rel="stylesheet" type="text/css" />
    <link href="https://assets-cdn.github.com/assets/github2-97fd69f3a3771e25d14b434fa06478cc54fb9bf3.css" media="all" rel="stylesheet" type="text/css" />
    


    <meta http-equiv="x-pjax-version" content="e4bf1707290e71c8a039593ba9decab6">

      
  <meta name="description" content="PredMachLearn_CourseProject - Prediction Assignment Writeup">


  <meta content="7771891" name="octolytics-dimension-user_id" /><meta content="McReyar" name="octolytics-dimension-user_login" /><meta content="23036611" name="octolytics-dimension-repository_id" /><meta content="McReyar/PredMachLearn_CourseProject" name="octolytics-dimension-repository_nwo" /><meta content="true" name="octolytics-dimension-repository_public" /><meta content="false" name="octolytics-dimension-repository_is_fork" /><meta content="23036611" name="octolytics-dimension-repository_network_root_id" /><meta content="McReyar/PredMachLearn_CourseProject" name="octolytics-dimension-repository_network_root_nwo" />
  <link href="https://github.com/McReyar/PredMachLearn_CourseProject/commits/gh-pages.atom" rel="alternate" title="Recent Commits to PredMachLearn_CourseProject:gh-pages" type="application/atom+xml">

  </head>


  <body class="logged_in  env-production windows vis-public page-blob">
    <a href="#start-of-content" tabindex="1" class="accessibility-aid js-skip-to-content">Skip to content</a>
    <div class="wrapper">
      
      
      
      


      <div class="header header-logged-in true">
  <div class="container clearfix">

    <a class="header-logo-invertocat" href="https://github.com/" aria-label="Homepage">
  <span class="mega-octicon octicon-mark-github"></span>
</a>


        <a href="/notifications" aria-label="You have no unread notifications" class="notification-indicator tooltipped tooltipped-s" data-hotkey="g n">
        <span class="mail-status all-read"></span>
</a>

      <div class="command-bar js-command-bar  in-repository">
          <form accept-charset="UTF-8" action="/search" class="command-bar-form" id="top_search_form" method="get"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /></div>

<div class="commandbar">
  <span class="message"></span>
  <input type="text" data-hotkey="s, /" name="q" id="js-command-bar-field" placeholder="Search or type a command" tabindex="1" autocapitalize="off"
    
    data-username="McReyar"
    data-repo="McReyar/PredMachLearn_CourseProject"
  >
  <div class="display hidden"></div>
</div>

    <input type="hidden" name="nwo" value="McReyar/PredMachLearn_CourseProject">

    <div class="select-menu js-menu-container js-select-menu search-context-select-menu">
      <span class="minibutton select-menu-button js-menu-target" role="button" aria-haspopup="true">
        <span class="js-select-button">This repository</span>
      </span>

      <div class="select-menu-modal-holder js-menu-content js-navigation-container" aria-hidden="true">
        <div class="select-menu-modal">

          <div class="select-menu-item js-navigation-item js-this-repository-navigation-item selected">
            <span class="select-menu-item-icon octicon octicon-check"></span>
            <input type="radio" class="js-search-this-repository" name="search_target" value="repository" checked="checked">
            <div class="select-menu-item-text js-select-button-text">This repository</div>
          </div> <!-- /.select-menu-item -->

          <div class="select-menu-item js-navigation-item js-all-repositories-navigation-item">
            <span class="select-menu-item-icon octicon octicon-check"></span>
            <input type="radio" name="search_target" value="global">
            <div class="select-menu-item-text js-select-button-text">All repositories</div>
          </div> <!-- /.select-menu-item -->

        </div>
      </div>
    </div>

  <span class="help tooltipped tooltipped-s" aria-label="Show command bar help">
    <span class="octicon octicon-question"></span>
  </span>


  <input type="hidden" name="ref" value="cmdform">

</form>
        <ul class="top-nav">
          <li class="explore"><a href="/explore">Explore</a></li>
            <li><a href="https://gist.github.com">Gist</a></li>
            <li><a href="/blog">Blog</a></li>
          <li><a href="https://help.github.com">Help</a></li>
        </ul>
      </div>

    
<ul id="user-links">
  <li>
    <a href="/McReyar" class="name">
      <img alt="McReyar" data-user="7771891" height="20" src="https://avatars1.githubusercontent.com/u/7771891?v=2&amp;s=40" width="20" /> McReyar
    </a>
  </li>

  <li class="new-menu dropdown-toggle js-menu-container">
    <a href="#" class="js-menu-target tooltipped tooltipped-s" aria-label="Create new...">
      <span class="octicon octicon-plus"></span>
      <span class="dropdown-arrow"></span>
    </a>

    <div class="new-menu-content js-menu-content">
    </div>
  </li>

  <li>
    <a href="/settings/profile" id="account_settings"
      class="tooltipped tooltipped-s"
      aria-label="Account settings ">
      <span class="octicon octicon-tools"></span>
    </a>
  </li>
  <li>
    <form accept-charset="UTF-8" action="/logout" class="logout-form" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="xDd8WHxnw7LX9r8EkV6J37GtF2E3lZnWEXx3e8kquK7W9Sb0G1l2f+u6UlHzIW7YQbNlbGDh8QSFM3CeVzCQFA==" /></div>
      <button class="sign-out-button tooltipped tooltipped-s" aria-label="Sign out">
        <span class="octicon octicon-sign-out"></span>
      </button>
</form>  </li>

</ul>

<div class="js-new-dropdown-contents hidden">
  
<ul class="dropdown-menu">
  <li>
    <a href="/new"><span class="octicon octicon-repo"></span> New repository</a>
  </li>
  <li>
    <a href="/organizations/new"><span class="octicon octicon-organization"></span> New organization</a>
  </li>


    <li class="section-title">
      <span title="McReyar/PredMachLearn_CourseProject">This repository</span>
    </li>
      <li>
        <a href="/McReyar/PredMachLearn_CourseProject/issues/new"><span class="octicon octicon-issue-opened"></span> New issue</a>
      </li>
      <li>
        <a href="/McReyar/PredMachLearn_CourseProject/settings/collaboration"><span class="octicon octicon-person"></span> New collaborator</a>
      </li>
</ul>

</div>


    
  </div>
</div>

      

        


      <div id="start-of-content" class="accessibility-aid"></div>
          <div class="site" itemscope itemtype="http://schema.org/WebPage">
    <div id="js-flash-container">
      
    </div>
    <div class="pagehead repohead instapaper_ignore readability-menu">
      <div class="container">
        
<ul class="pagehead-actions">

    <li class="subscription">
      <form accept-charset="UTF-8" action="/notifications/subscribe" class="js-social-container" data-autosubmit="true" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="yTKeHo45IJPXQ0VZzo9J/Z3u6GofpYSoJRL44XQhzXjYi4iMdJXEkCs0RTZMIH/atv3zfxJZU6NNwHVQqd2yUA==" /></div>  <input id="repository_id" name="repository_id" type="hidden" value="23036611" />

    <div class="select-menu js-menu-container js-select-menu">
      <a class="social-count js-social-count" href="/McReyar/PredMachLearn_CourseProject/watchers">
        1
      </a>
      <a href="/McReyar/PredMachLearn_CourseProject/subscription"
        class="minibutton select-menu-button with-count js-menu-target" role="button" tabindex="0" aria-haspopup="true">
        <span class="js-select-button">
          <span class="octicon octicon-eye"></span>
          Unwatch
        </span>
      </a>

      <div class="select-menu-modal-holder">
        <div class="select-menu-modal subscription-menu-modal js-menu-content" aria-hidden="true">
          <div class="select-menu-header">
            <span class="select-menu-title">Notifications</span>
            <span class="octicon octicon-x js-menu-close" role="button" aria-label="Close"></span>
          </div> <!-- /.select-menu-header -->

          <div class="select-menu-list js-navigation-container" role="menu">

            <div class="select-menu-item js-navigation-item " role="menuitem" tabindex="0">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <div class="select-menu-item-text">
                <input id="do_included" name="do" type="radio" value="included" />
                <h4>Not watching</h4>
                <span class="description">Be notified when participating or @mentioned.</span>
                <span class="js-select-button-text hidden-select-button-text">
                  <span class="octicon octicon-eye"></span>
                  Watch
                </span>
              </div>
            </div> <!-- /.select-menu-item -->

            <div class="select-menu-item js-navigation-item selected" role="menuitem" tabindex="0">
              <span class="select-menu-item-icon octicon octicon octicon-check"></span>
              <div class="select-menu-item-text">
                <input checked="checked" id="do_subscribed" name="do" type="radio" value="subscribed" />
                <h4>Watching</h4>
                <span class="description">Be notified of all conversations.</span>
                <span class="js-select-button-text hidden-select-button-text">
                  <span class="octicon octicon-eye"></span>
                  Unwatch
                </span>
              </div>
            </div> <!-- /.select-menu-item -->

            <div class="select-menu-item js-navigation-item " role="menuitem" tabindex="0">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <div class="select-menu-item-text">
                <input id="do_ignore" name="do" type="radio" value="ignore" />
                <h4>Ignoring</h4>
                <span class="description">Never be notified.</span>
                <span class="js-select-button-text hidden-select-button-text">
                  <span class="octicon octicon-mute"></span>
                  Stop ignoring
                </span>
              </div>
            </div> <!-- /.select-menu-item -->

          </div> <!-- /.select-menu-list -->

        </div> <!-- /.select-menu-modal -->
      </div> <!-- /.select-menu-modal-holder -->
    </div> <!-- /.select-menu -->

</form>
    </li>

  <li>
    
  <div class="js-toggler-container js-social-container starring-container ">

    <form accept-charset="UTF-8" action="/McReyar/PredMachLearn_CourseProject/unstar" class="js-toggler-form starred js-unstar-button" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="PUlCKQWmW/IHkWx2aBtGfnXdbK3ioJZ4D4AJJjAbmRs2vz5zwRrwDSwi1Yh2Fr7SHk+VFLJA4HK2lrdFUNkHzA==" /></div>
      <button
        class="minibutton with-count js-toggler-target star-button"
        aria-label="Unstar this repository" title="Unstar McReyar/PredMachLearn_CourseProject">
        <span class="octicon octicon-star"></span>
        Unstar
      </button>
        <a class="social-count js-social-count" href="/McReyar/PredMachLearn_CourseProject/stargazers">
          0
        </a>
</form>
    <form accept-charset="UTF-8" action="/McReyar/PredMachLearn_CourseProject/star" class="js-toggler-form unstarred js-star-button" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="0IV6JiBZmNyT1gWf1rc+eEANQ5HcrFrtX189rHlGSQy9vCql8QkOpcOBBjnSO9Q/ORlnAgkAeSVjVnGO4MCDeg==" /></div>
      <button
        class="minibutton with-count js-toggler-target star-button"
        aria-label="Star this repository" title="Star McReyar/PredMachLearn_CourseProject">
        <span class="octicon octicon-star"></span>
        Star
      </button>
        <a class="social-count js-social-count" href="/McReyar/PredMachLearn_CourseProject/stargazers">
          0
        </a>
</form>  </div>

  </li>


        <li>
          <a href="/McReyar/PredMachLearn_CourseProject/fork" class="minibutton with-count js-toggler-target fork-button lighter tooltipped-n" title="Fork your own copy of McReyar/PredMachLearn_CourseProject to your account" aria-label="Fork your own copy of McReyar/PredMachLearn_CourseProject to your account" rel="nofollow" data-method="post">
            <span class="octicon octicon-repo-forked"></span>
            Fork
          </a>
          <a href="/McReyar/PredMachLearn_CourseProject/network" class="social-count">0</a>
        </li>

</ul>

        <h1 itemscope itemtype="http://data-vocabulary.org/Breadcrumb" class="entry-title public">
          <span class="mega-octicon octicon-repo"></span>
          <span class="author"><a href="/McReyar" class="url fn" itemprop="url" rel="author"><span itemprop="title">McReyar</span></a></span><!--
       --><span class="path-divider">/</span><!--
       --><strong><a href="/McReyar/PredMachLearn_CourseProject" class="js-current-repository js-repo-home-link">PredMachLearn_CourseProject</a></strong>

          <span class="page-context-loader">
            <img alt="" height="16" src="https://assets-cdn.github.com/images/spinners/octocat-spinner-32.gif" width="16" />
          </span>

        </h1>
      </div><!-- /.container -->
    </div><!-- /.repohead -->

    <div class="container">
      <div class="repository-with-sidebar repo-container new-discussion-timeline  ">
        <div class="repository-sidebar clearfix">
            
<div class="sunken-menu vertical-right repo-nav js-repo-nav js-repository-container-pjax js-octicon-loaders" data-issue-count-url="/McReyar/PredMachLearn_CourseProject/issues/counts">
  <div class="sunken-menu-contents">
    <ul class="sunken-menu-group">
      <li class="tooltipped tooltipped-w" aria-label="Code">
        <a href="/McReyar/PredMachLearn_CourseProject/tree/gh-pages" aria-label="Code" class="selected js-selected-navigation-item sunken-menu-item" data-hotkey="g c" data-pjax="true" data-selected-links="repo_source repo_downloads repo_commits repo_releases repo_tags repo_branches /McReyar/PredMachLearn_CourseProject/tree/gh-pages">
          <span class="octicon octicon-code"></span> <span class="full-word">Code</span>
          <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/images/spinners/octocat-spinner-32.gif" width="16" />
</a>      </li>

        <li class="tooltipped tooltipped-w" aria-label="Issues">
          <a href="/McReyar/PredMachLearn_CourseProject/issues" aria-label="Issues" class="js-selected-navigation-item sunken-menu-item js-disable-pjax" data-hotkey="g i" data-selected-links="repo_issues repo_labels repo_milestones /McReyar/PredMachLearn_CourseProject/issues">
            <span class="octicon octicon-issue-opened"></span> <span class="full-word">Issues</span>
            <span class="js-issue-replace-counter"></span>
            <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/images/spinners/octocat-spinner-32.gif" width="16" />
</a>        </li>

      <li class="tooltipped tooltipped-w" aria-label="Pull Requests">
        <a href="/McReyar/PredMachLearn_CourseProject/pulls" aria-label="Pull Requests" class="js-selected-navigation-item sunken-menu-item js-disable-pjax" data-hotkey="g p" data-selected-links="repo_pulls /McReyar/PredMachLearn_CourseProject/pulls">
            <span class="octicon octicon-git-pull-request"></span> <span class="full-word">Pull Requests</span>
            <span class="js-pull-replace-counter"></span>
            <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/images/spinners/octocat-spinner-32.gif" width="16" />
</a>      </li>


        <li class="tooltipped tooltipped-w" aria-label="Wiki">
          <a href="/McReyar/PredMachLearn_CourseProject/wiki" aria-label="Wiki" class="js-selected-navigation-item sunken-menu-item js-disable-pjax" data-hotkey="g w" data-selected-links="repo_wiki /McReyar/PredMachLearn_CourseProject/wiki">
            <span class="octicon octicon-book"></span> <span class="full-word">Wiki</span>
            <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/images/spinners/octocat-spinner-32.gif" width="16" />
</a>        </li>
    </ul>
    <div class="sunken-menu-separator"></div>
    <ul class="sunken-menu-group">

      <li class="tooltipped tooltipped-w" aria-label="Pulse">
        <a href="/McReyar/PredMachLearn_CourseProject/pulse/weekly" aria-label="Pulse" class="js-selected-navigation-item sunken-menu-item" data-pjax="true" data-selected-links="pulse /McReyar/PredMachLearn_CourseProject/pulse/weekly">
          <span class="octicon octicon-pulse"></span> <span class="full-word">Pulse</span>
          <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/images/spinners/octocat-spinner-32.gif" width="16" />
</a>      </li>

      <li class="tooltipped tooltipped-w" aria-label="Graphs">
        <a href="/McReyar/PredMachLearn_CourseProject/graphs" aria-label="Graphs" class="js-selected-navigation-item sunken-menu-item" data-pjax="true" data-selected-links="repo_graphs repo_contributors /McReyar/PredMachLearn_CourseProject/graphs">
          <span class="octicon octicon-graph"></span> <span class="full-word">Graphs</span>
          <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/images/spinners/octocat-spinner-32.gif" width="16" />
</a>      </li>
    </ul>


      <div class="sunken-menu-separator"></div>
      <ul class="sunken-menu-group">
        <li class="tooltipped tooltipped-w" aria-label="Settings">
          <a href="/McReyar/PredMachLearn_CourseProject/settings" aria-label="Settings" class="js-selected-navigation-item sunken-menu-item" data-pjax="true" data-selected-links="repo_settings /McReyar/PredMachLearn_CourseProject/settings">
            <span class="octicon octicon-tools"></span> <span class="full-word">Settings</span>
            <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/images/spinners/octocat-spinner-32.gif" width="16" />
</a>        </li>
      </ul>
  </div>
</div>

              <div class="only-with-full-nav">
                
  
<div class="clone-url open"
  data-protocol-type="http"
  data-url="/users/set_protocol?protocol_selector=http&amp;protocol_type=push">
  <h3><strong>HTTPS</strong> clone URL</h3>
  <div class="input-group">
    <input type="text" class="input-mini input-monospace js-url-field"
           value="https://github.com/McReyar/PredMachLearn_CourseProject.git" readonly="readonly">
    <span class="input-group-button">
      <button aria-label="Copy to clipboard" class="js-zeroclipboard minibutton zeroclipboard-button" data-clipboard-text="https://github.com/McReyar/PredMachLearn_CourseProject.git" data-copied-hint="Copied!" type="button"><span class="octicon octicon-clippy"></span></button>
    </span>
  </div>
</div>

  
<div class="clone-url "
  data-protocol-type="ssh"
  data-url="/users/set_protocol?protocol_selector=ssh&amp;protocol_type=push">
  <h3><strong>SSH</strong> clone URL</h3>
  <div class="input-group">
    <input type="text" class="input-mini input-monospace js-url-field"
           value="git@github.com:McReyar/PredMachLearn_CourseProject.git" readonly="readonly">
    <span class="input-group-button">
      <button aria-label="Copy to clipboard" class="js-zeroclipboard minibutton zeroclipboard-button" data-clipboard-text="git@github.com:McReyar/PredMachLearn_CourseProject.git" data-copied-hint="Copied!" type="button"><span class="octicon octicon-clippy"></span></button>
    </span>
  </div>
</div>

  
<div class="clone-url "
  data-protocol-type="subversion"
  data-url="/users/set_protocol?protocol_selector=subversion&amp;protocol_type=push">
  <h3><strong>Subversion</strong> checkout URL</h3>
  <div class="input-group">
    <input type="text" class="input-mini input-monospace js-url-field"
           value="https://github.com/McReyar/PredMachLearn_CourseProject" readonly="readonly">
    <span class="input-group-button">
      <button aria-label="Copy to clipboard" class="js-zeroclipboard minibutton zeroclipboard-button" data-clipboard-text="https://github.com/McReyar/PredMachLearn_CourseProject" data-copied-hint="Copied!" type="button"><span class="octicon octicon-clippy"></span></button>
    </span>
  </div>
</div>


<p class="clone-options">You can clone with
      <a href="#" class="js-clone-selector" data-protocol="http">HTTPS</a>,
      <a href="#" class="js-clone-selector" data-protocol="ssh">SSH</a>,
      or <a href="#" class="js-clone-selector" data-protocol="subversion">Subversion</a>.
  <a href="https://help.github.com/articles/which-remote-url-should-i-use" class="help tooltipped tooltipped-n" aria-label="Get help on which URL is right for you.">
    <span class="octicon octicon-question"></span>
  </a>
</p>


  <a href="http://windows.github.com" class="minibutton sidebar-button" title="Save McReyar/PredMachLearn_CourseProject to your computer and use it in GitHub Desktop." aria-label="Save McReyar/PredMachLearn_CourseProject to your computer and use it in GitHub Desktop.">
    <span class="octicon octicon-device-desktop"></span>
    Clone in Desktop
  </a>

                <a href="/McReyar/PredMachLearn_CourseProject/archive/gh-pages.zip"
                   class="minibutton sidebar-button"
                   aria-label="Download McReyar/PredMachLearn_CourseProject as a zip file"
                   title="Download McReyar/PredMachLearn_CourseProject as a zip file"
                   rel="nofollow">
                  <span class="octicon octicon-cloud-download"></span>
                  Download ZIP
                </a>
              </div>
        </div><!-- /.repository-sidebar -->

        <div id="js-repo-pjax-container" class="repository-content context-loader-container" data-pjax-container>
          

<a href="/McReyar/PredMachLearn_CourseProject/blob/6124ddb4dac449d455ce640306aad50992eaf946/README.md" class="hidden js-permalink-shortcut" data-hotkey="y">Permalink</a>

<!-- blob contrib key: blob_contributors:v21:602e8e14fc7da9c51a2d5feb9fdda9de -->

<div class="file-navigation">
  
<div class="select-menu js-menu-container js-select-menu left">
  <span class="minibutton select-menu-button js-menu-target css-truncate" data-hotkey="w"
    data-master-branch="master"
    data-ref="gh-pages"
    title="gh-pages"
    role="button" aria-label="Switch branches or tags" tabindex="0" aria-haspopup="true">
    <span class="octicon octicon-git-branch"></span>
    <i>branch:</i>
    <span class="js-select-button css-truncate-target">gh-pages</span>
  </span>

  <div class="select-menu-modal-holder js-menu-content js-navigation-container" data-pjax aria-hidden="true">

    <div class="select-menu-modal">
      <div class="select-menu-header">
        <span class="select-menu-title">Switch branches/tags</span>
        <span class="octicon octicon-x js-menu-close" role="button" aria-label="Close"></span>
      </div> <!-- /.select-menu-header -->

      <div class="select-menu-filters">
        <div class="select-menu-text-filter">
          <input type="text" aria-label="Find or create a branch…" id="context-commitish-filter-field" class="js-filterable-field js-navigation-enable" placeholder="Find or create a branch…">
        </div>
        <div class="select-menu-tabs">
          <ul>
            <li class="select-menu-tab">
              <a href="#" data-tab-filter="branches" class="js-select-menu-tab">Branches</a>
            </li>
            <li class="select-menu-tab">
              <a href="#" data-tab-filter="tags" class="js-select-menu-tab">Tags</a>
            </li>
          </ul>
        </div><!-- /.select-menu-tabs -->
      </div><!-- /.select-menu-filters -->

      <div class="select-menu-list select-menu-tab-bucket js-select-menu-tab-bucket" data-tab-filter="branches">

        <div data-filterable-for="context-commitish-filter-field" data-filterable-type="substring">


            <div class="select-menu-item js-navigation-item selected">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <a href="/McReyar/PredMachLearn_CourseProject/blob/gh-pages/README.md"
                 data-name="gh-pages"
                 data-skip-pjax="true"
                 rel="nofollow"
                 class="js-navigation-open select-menu-item-text css-truncate-target"
                 title="gh-pages">gh-pages</a>
            </div> <!-- /.select-menu-item -->
            <div class="select-menu-item js-navigation-item ">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <a href="/McReyar/PredMachLearn_CourseProject/blob/master/README.md"
                 data-name="master"
                 data-skip-pjax="true"
                 rel="nofollow"
                 class="js-navigation-open select-menu-item-text css-truncate-target"
                 title="master">master</a>
            </div> <!-- /.select-menu-item -->
        </div>

          <form accept-charset="UTF-8" action="/McReyar/PredMachLearn_CourseProject/branches" class="js-create-branch select-menu-item select-menu-new-item-form js-navigation-item js-new-item-form" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="BRXUPmH2fm8k5zLcXl0Ut3Il5fLbWejHYv1bTZcL6qsk4qZyOg3bOo1TKFOEJsQFNDfPqTxx/QOmFfP9zerMRw==" /></div>
            <span class="octicon octicon-git-branch select-menu-item-icon"></span>
            <div class="select-menu-item-text">
              <h4>Create branch: <span class="js-new-item-name"></span></h4>
              <span class="description">from ‘gh-pages’</span>
            </div>
            <input type="hidden" name="name" id="name" class="js-new-item-value">
            <input type="hidden" name="branch" id="branch" value="gh-pages">
            <input type="hidden" name="path" id="path" value="README.md">
          </form> <!-- /.select-menu-item -->

      </div> <!-- /.select-menu-list -->

      <div class="select-menu-list select-menu-tab-bucket js-select-menu-tab-bucket" data-tab-filter="tags">
        <div data-filterable-for="context-commitish-filter-field" data-filterable-type="substring">


        </div>

        <div class="select-menu-no-results">Nothing to show</div>
      </div> <!-- /.select-menu-list -->

    </div> <!-- /.select-menu-modal -->
  </div> <!-- /.select-menu-modal-holder -->
</div> <!-- /.select-menu -->

  <div class="button-group right">
    <a href="/McReyar/PredMachLearn_CourseProject/find/gh-pages"
          class="js-show-file-finder minibutton empty-icon tooltipped tooltipped-s"
          data-pjax
          data-hotkey="t"
          aria-label="Quickly jump between files">
      <span class="octicon octicon-list-unordered"></span>
    </a>
    <button class="js-zeroclipboard minibutton zeroclipboard-button"
          data-clipboard-text="README.md"
          aria-label="Copy to clipboard"
          data-copied-hint="Copied!">
      <span class="octicon octicon-clippy"></span>
    </button>
  </div>

  <div class="breadcrumb">
    <span class='repo-root js-repo-root'><span itemscope="" itemtype="http://data-vocabulary.org/Breadcrumb"><a href="/McReyar/PredMachLearn_CourseProject/tree/gh-pages" class="" data-branch="gh-pages" data-direction="back" data-pjax="true" itemscope="url"><span itemprop="title">PredMachLearn_CourseProject</span></a></span></span><span class="separator"> / </span><strong class="final-path">README.md</strong>
  </div>
</div>


  <div class="commit file-history-tease">
      <img alt="McReyar" class="main-avatar" data-user="7771891" height="24" src="https://avatars3.githubusercontent.com/u/7771891?v=2&amp;s=48" width="24" />
      <span class="author"><a href="/McReyar" rel="author">McReyar</a></span>
      <time datetime="2014-08-17T14:33:48+02:00" is="relative-time">August 17, 2014</time>
      <div class="commit-title">
          <a href="/McReyar/PredMachLearn_CourseProject/commit/6124ddb4dac449d455ce640306aad50992eaf946" class="message" data-pjax="true" title="README.md">README.md</a>
      </div>

    <div class="participation">
      <p class="quickstat"><a href="#blob_contributors_box" rel="facebox"><strong>1</strong>  contributor</a></p>
      

    </div>
    <div id="blob_contributors_box" style="display:none">
      <h2 class="facebox-header">Users who have contributed to this file</h2>
      <ul class="facebox-user-list">
          <li class="facebox-user-list-item">
            <img alt="McReyar" data-user="7771891" height="24" src="https://avatars3.githubusercontent.com/u/7771891?v=2&amp;s=48" width="24" />
            <a href="/McReyar">McReyar</a>
          </li>
      </ul>
    </div>
  </div>

<div class="file-box">
  <div class="file">
    <div class="meta clearfix">
      <div class="info file-name">
          <span>436 lines (390 sloc)</span>
          <span class="meta-divider"></span>
        <span>13.869 kb</span>
      </div>
      <div class="actions">
        <div class="button-group">
          <a href="/McReyar/PredMachLearn_CourseProject/raw/gh-pages/README.md" class="minibutton " id="raw-url">Raw</a>
            <a href="/McReyar/PredMachLearn_CourseProject/blame/gh-pages/README.md" class="minibutton js-update-url-with-hash">Blame</a>
          <a href="/McReyar/PredMachLearn_CourseProject/commits/gh-pages/README.md" class="minibutton " rel="nofollow">History</a>
        </div><!-- /.button-group -->

          <a class="octicon-button tooltipped tooltipped-nw"
             href="http://windows.github.com" aria-label="Open this file in GitHub for Windows">
              <span class="octicon octicon-device-desktop"></span>
          </a>

              <a class="octicon-button js-update-url-with-hash"
                 href="/McReyar/PredMachLearn_CourseProject/edit/gh-pages/README.md"
                 data-method="post" rel="nofollow" data-hotkey="e"><span class="octicon octicon-pencil"></span></a>

            <a class="octicon-button danger"
               href="/McReyar/PredMachLearn_CourseProject/delete/gh-pages/README.md"
               data-method="post" data-test-id="delete-blob-file" rel="nofollow">
          <span class="octicon octicon-trashcan"></span>
        </a>
      </div><!-- /.actions -->
    </div>
        <div id="readme" class="blob instapaper_body">
    <article class="markdown-body entry-content" itemprop="mainContentOfPage"><h1>
<a name="user-content-predicting-exercise-type" class="anchor" href="#predicting-exercise-type" aria-hidden="true"><span class="octicon octicon-link"></span></a>Predicting Exercise Type</h1>

<p>McReyar<br>
Practical Machine Learning (predmachlearn-004) / Coursera  </p>

<h2>
<a name="user-content-synopsis" class="anchor" href="#synopsis" aria-hidden="true"><span class="octicon octicon-link"></span></a>Synopsis</h2>

<p>In this paper activities are predicted based on the data of wearable accelerometers. After loading and preprocessing the data, several different models and tuning parameters are built and the best model is selected. Finally the best model is used to make predictions on a test dataset.</p>

<h2>
<a name="user-content-data-preparation" class="anchor" href="#data-preparation" aria-hidden="true"><span class="octicon octicon-link"></span></a>Data Preparation</h2>

<p>Following libraries are used for this project:</p>

<div class="highlight highlight-r"><pre><span class="kn">library</span><span class="p">(</span>knitr<span class="p">)</span>
<span class="kn">library</span><span class="p">(</span>lattice<span class="p">)</span>
<span class="kn">library</span><span class="p">(</span>ggplot2<span class="p">)</span>
<span class="kn">library</span><span class="p">(</span>caret<span class="p">)</span>
<span class="kn">library</span><span class="p">(</span>glmnet<span class="p">)</span>
</pre></div>

<pre><code>## Loading required package: Matrix
## Loaded glmnet 1.9-8
</code></pre>

<div class="highlight highlight-r"><pre><span class="kn">library</span><span class="p">(</span>rpart<span class="p">)</span>
<span class="kn">library</span><span class="p">(</span>kernlab<span class="p">)</span>
<span class="kn">library</span><span class="p">(</span>randomForest<span class="p">)</span>
</pre></div>

<pre><code>## randomForest 4.6-10
## Type rfNews() to see new features/changes/bug fixes.
</code></pre>

<h3>
<a name="user-content-data-source-and-format" class="anchor" href="#data-source-and-format" aria-hidden="true"><span class="octicon octicon-link"></span></a>Data Source and Format</h3>

<p>For the analysis the dataset <a href="http://groupware.les.inf.puc-rio.br/har">Human Activity Recognition</a> is used which was gathered by Velloso, Bulling, Gellersen, Ugulino and Fuks[^1].</p>

<div class="highlight highlight-r"><pre><span class="kr">if</span><span class="p">(</span><span class="o">!</span><span class="kp">file.exists</span><span class="p">(</span><span class="s">"pml-training.csv"</span><span class="p">)</span> <span class="o">|</span> <span class="o">!</span><span class="kp">file.exists</span><span class="p">(</span><span class="s">"pml-testing.csv"</span><span class="p">))</span> <span class="p">{</span>
    download.file<span class="p">(</span><span class="s">"http://d396qusza40orc.cloudfront.net/predmachlearn/pml-training.csv"</span>
                 <span class="p">,</span>destfile <span class="o">=</span> <span class="s">"pml-training.csv"</span><span class="p">)</span>
    download.file<span class="p">(</span><span class="s">"http://d396qusza40orc.cloudfront.net/predmachlearn/pml-testing.csv"</span>
                 <span class="p">,</span>destfile <span class="o">=</span> <span class="s">"pml-testing.csv"</span><span class="p">)</span>
    download.date <span class="o">&lt;-</span> <span class="kp">format</span><span class="p">(</span><span class="kp">Sys.time</span><span class="p">(),</span><span class="s">"%m/%d/%Y %I:%M %p %Z"</span><span class="p">,</span> tz <span class="o">=</span> <span class="s">"UTC"</span><span class="p">)</span>
<span class="p">}</span>
</pre></div>

<p>For this paper the file has been downloaded on 08/17/2014 09:58 AM UTC.</p>

<p>The data is separated by commas and "NA", "" or "#DIV/0!" are interpreted as missing values. The first 7 columns aren't read, because they include IDs, names, timestamps and other data that is not relevant for the analysis.</p>

<div class="highlight highlight-r"><pre>pml      <span class="o">&lt;-</span> read.csv<span class="p">(</span><span class="s">"pml-training.csv"</span><span class="p">,</span> na.strings <span class="o">=</span> <span class="kt">c</span><span class="p">(</span><span class="s">"\"\""</span><span class="p">,</span><span class="s">"NA"</span><span class="p">,</span><span class="s">"#DIV/0!"</span><span class="p">)</span>
                    <span class="p">,</span>colClasses <span class="o">=</span> <span class="kt">c</span><span class="p">(</span><span class="kp">rep</span><span class="p">(</span><span class="s">"NULL"</span><span class="p">,</span><span class="m">7</span><span class="p">),</span><span class="kp">rep</span><span class="p">(</span><span class="kc">NA</span><span class="p">,</span><span class="m">152</span><span class="p">),</span><span class="s">"factor"</span><span class="p">))</span>
predict  <span class="o">&lt;-</span> read.csv<span class="p">(</span><span class="s">"pml-testing.csv"</span><span class="p">,</span> na.strings <span class="o">=</span> <span class="kt">c</span><span class="p">(</span><span class="s">"\"\""</span><span class="p">,</span><span class="s">"NA"</span><span class="p">,</span><span class="s">"#DIV/0!"</span><span class="p">)</span>
                    <span class="p">,</span>colClasses <span class="o">=</span> <span class="kt">c</span><span class="p">(</span><span class="kp">rep</span><span class="p">(</span><span class="s">"NULL"</span><span class="p">,</span><span class="m">7</span><span class="p">),</span><span class="kp">rep</span><span class="p">(</span><span class="kc">NA</span><span class="p">,</span><span class="m">152</span><span class="p">),</span><span class="s">"NULL"</span><span class="p">))</span>
</pre></div>

<p>For estimating the out of sample error, 30% of the data is set aside as testing set.</p>

<div class="highlight highlight-r"><pre><span class="kp">set.seed</span><span class="p">(</span><span class="m">157885</span><span class="p">)</span>
inTrain <span class="o">&lt;-</span> <span class="kp">sort</span><span class="p">(</span>createDataPartition<span class="p">(</span>y <span class="o">=</span> pml<span class="o">$</span>classe<span class="p">,</span> p <span class="o">=</span> <span class="m">0.7</span><span class="p">,</span> <span class="kt">list</span> <span class="o">=</span> <span class="kc">FALSE</span><span class="p">))</span>
training   <span class="o">&lt;-</span> pml<span class="p">[</span> inTrain<span class="p">,]</span>
testing    <span class="o">&lt;-</span> pml<span class="p">[</span><span class="o">-</span>inTrain<span class="p">,]</span>
</pre></div>

<h3>
<a name="user-content-missing-values" class="anchor" href="#missing-values" aria-hidden="true"><span class="octicon octicon-link"></span></a>Missing Values</h3>

<div class="highlight highlight-r"><pre>naCols <span class="o">&lt;-</span> <span class="kp">colSums</span><span class="p">(</span><span class="kp">is.na</span><span class="p">(</span>training<span class="p">))</span>
sumMissing <span class="o">&lt;-</span> <span class="kp">sum</span><span class="p">(</span>naCols <span class="o">&gt;</span> <span class="m">0</span><span class="p">)</span>
minMissing <span class="o">&lt;-</span> <span class="kp">min</span><span class="p">(</span>naCols<span class="p">[</span>naCols <span class="o">&gt;</span> <span class="m">0</span><span class="p">])</span>
</pre></div>

<p>There are 100 columns with missing values and for each of these the values are missing for the majority of rows (at least 13452). Because of this, imputing the missing values  isn't feasible and the columns are therefore discarded for further analysis. </p>

<div class="highlight highlight-r"><pre><span class="kr">for</span><span class="p">(</span>n <span class="kr">in</span> <span class="kp">seq</span><span class="p">(</span><span class="kp">ncol</span><span class="p">(</span>training<span class="p">),</span><span class="m">1</span><span class="p">))</span> <span class="p">{</span>
    <span class="kr">if</span><span class="p">(</span>naCols<span class="p">[</span>n<span class="p">]</span> <span class="o">&gt;</span> <span class="m">0</span><span class="p">)</span> <span class="p">{</span>
        training<span class="p">[,</span>n<span class="p">]</span> <span class="o">&lt;-</span> <span class="kc">NULL</span>
        testing<span class="p">[,</span>n<span class="p">]</span>  <span class="o">&lt;-</span> <span class="kc">NULL</span>
        pml<span class="p">[,</span>n<span class="p">]</span>      <span class="o">&lt;-</span> <span class="kc">NULL</span>
        predict<span class="p">[,</span>n<span class="p">]</span>  <span class="o">&lt;-</span> <span class="kc">NULL</span>
    <span class="p">}</span>
<span class="p">}</span>
<span class="kp">dim</span><span class="p">(</span>training<span class="p">)</span>
</pre></div>

<pre><code>## [1] 13737    53
</code></pre>

<p>Because there are still 53 columns left, a summary isn't printed in this paper, although it was checked for the analysis.</p>

<h2>
<a name="user-content-training-models" class="anchor" href="#training-models" aria-hidden="true"><span class="octicon octicon-link"></span></a>Training Models</h2>

<p>The activity classes have following frequencies</p>

<div class="highlight highlight-r"><pre>kable<span class="p">(</span><span class="kt">data.frame</span><span class="p">(</span>Activity  <span class="o">=</span> <span class="kp">levels</span><span class="p">(</span>training<span class="o">$</span>classe<span class="p">)</span>
                <span class="p">,</span>Frequency <span class="o">=</span> <span class="kp">paste0</span><span class="p">(</span><span class="kp">round</span><span class="p">(</span><span class="m">100</span><span class="o">*</span><span class="kp">prop.table</span><span class="p">(</span><span class="kp">table</span><span class="p">(</span>training<span class="o">$</span>classe<span class="p">)),</span><span class="m">2</span><span class="p">),</span><span class="s">"%"</span><span class="p">)</span>
                <span class="p">)</span>
     <span class="p">,</span>format <span class="o">=</span> <span class="s">"html"</span><span class="p">)</span>
</pre></div>

<table>
<thead><tr>
<th align="left"> Activity </th>
   <th align="left"> Frequency </th>
  </tr></thead>
<tbody>
<tr>
<td align="left"> A </td>
   <td align="left"> 28.43% </td>
  </tr>
<tr>
<td align="left"> B </td>
   <td align="left"> 19.35% </td>
  </tr>
<tr>
<td align="left"> C </td>
   <td align="left"> 17.44% </td>
  </tr>
<tr>
<td align="left"> D </td>
   <td align="left"> 16.39% </td>
  </tr>
<tr>
<td align="left"> E </td>
   <td align="left"> 18.38% </td>
  </tr>
</tbody>
</table><p>Therefore the baseline for our model is an accuracy of 28.43%.  </p>

<p>For tuning the models 5-fold cross validation is used.</p>

<div class="highlight highlight-r"><pre>trControl <span class="o">&lt;-</span> trainControl<span class="p">(</span>method <span class="o">=</span> <span class="s">"cv"</span><span class="p">,</span> number <span class="o">=</span> <span class="m">5</span><span class="p">)</span>
</pre></div>

<p>To get the best final model following methods are used and compared:</p>

<ul class="task-list">
<li>Regularized Generalized Linear Model</li>
<li>Decision Tree</li>
<li>Support Vector Machine (linear kernel)</li>
<li>Support Vector Machine (radial kernel)</li>
<li>Random Forest<br>
For all models numeric values are centered and scaled.</li>
</ul><h3>
<a name="user-content-regularized-generalized-linear-model-glmnet" class="anchor" href="#regularized-generalized-linear-model-glmnet" aria-hidden="true"><span class="octicon octicon-link"></span></a>Regularized Generalized Linear Model (glmnet)</h3>

<div class="highlight highlight-r"><pre><span class="kp">set.seed</span><span class="p">(</span><span class="m">157885</span><span class="p">)</span>
model.glm <span class="o">&lt;-</span> train<span class="p">(</span>classe <span class="o">~</span> <span class="m">.</span><span class="p">,</span> data <span class="o">=</span> training<span class="p">,</span> method <span class="o">=</span> <span class="s">"glmnet"</span>
                   <span class="p">,</span>trControl <span class="o">=</span> trControl<span class="p">,</span> preProcess <span class="o">=</span> <span class="kt">c</span><span class="p">(</span><span class="s">"center"</span><span class="p">,</span><span class="s">"scale"</span><span class="p">)</span>
<span class="p">)</span>
<span class="kp">print</span><span class="p">(</span>model.glm<span class="p">)</span>
</pre></div>

<pre><code>## glmnet 
## 
## 13737 samples
##    52 predictors
##     5 classes: 'A', 'B', 'C', 'D', 'E' 
## 
## Pre-processing: centered, scaled 
## Resampling: Cross-Validated (5 fold) 
## 
## Summary of sample sizes: 10989, 10991, 10989, 10990, 10989 
## 
## Resampling results across tuning parameters:
## 
##   alpha  lambda  Accuracy  Kappa  Accuracy SD  Kappa SD
##   0.1    0.1     0.5       0.4    0.01         0.02    
##   0.1    0.5     0.4       0.1    0.001        0.001   
##   0.1    0.8     0.3       9e-04  5e-04        5e-04   
##   0.1    1       0.3       0      2e-04        0       
##   0.1    2       0.3       0      2e-04        0       
##   0.1    2       0.3       0      2e-04        0       
##   0.1    2       0.3       0      2e-04        0       
##   0.1    3       0.3       0      2e-04        0       
##   0.1    3       0.3       0      2e-04        0       
##   0.6    0.1     0.4       0.2    0.007        0.009   
##   0.6    0.5     0.3       0      2e-04        0       
##   0.6    0.8     0.3       0      2e-04        0       
##   0.6    1       0.3       0      2e-04        0       
##   0.6    2       0.3       0      2e-04        0       
##   0.6    2       0.3       0      2e-04        0       
##   0.6    2       0.3       0      2e-04        0       
##   0.6    3       0.3       0      2e-04        0       
##   0.6    3       0.3       0      2e-04        0       
##   1      0.1     0.3       0.07   0.005        0.007   
##   1      0.5     0.3       0      2e-04        0       
##   1      0.8     0.3       0      2e-04        0       
##   1      1       0.3       0      2e-04        0       
##   1      2       0.3       0      2e-04        0       
##   1      2       0.3       0      2e-04        0       
##   1      2       0.3       0      2e-04        0       
##   1      3       0.3       0      2e-04        0       
##   1      3       0.3       0      2e-04        0       
## 
## Accuracy was used to select the optimal model using  the largest value.
## The final values used for the model were alpha = 0.1 and lambda = 0.1.
</code></pre>

<h3>
<a name="user-content-decision-tree-cart" class="anchor" href="#decision-tree-cart" aria-hidden="true"><span class="octicon octicon-link"></span></a>Decision Tree (CART)</h3>

<div class="highlight highlight-r"><pre><span class="kp">set.seed</span><span class="p">(</span><span class="m">157885</span><span class="p">)</span>
model.rpart <span class="o">&lt;-</span> train<span class="p">(</span>classe <span class="o">~</span> <span class="m">.</span><span class="p">,</span> data <span class="o">=</span> training<span class="p">,</span> method <span class="o">=</span> <span class="s">"rpart"</span>
                     <span class="p">,</span>trControl <span class="o">=</span> trControl<span class="p">,</span> preProcess <span class="o">=</span> <span class="kt">c</span><span class="p">(</span><span class="s">"center"</span><span class="p">,</span><span class="s">"scale"</span><span class="p">)</span>
<span class="p">)</span>
<span class="kp">print</span><span class="p">(</span>model.rpart<span class="p">)</span>
</pre></div>

<pre><code>## CART 
## 
## 13737 samples
##    52 predictors
##     5 classes: 'A', 'B', 'C', 'D', 'E' 
## 
## Pre-processing: centered, scaled 
## Resampling: Cross-Validated (5 fold) 
## 
## Summary of sample sizes: 10989, 10991, 10989, 10990, 10989 
## 
## Resampling results across tuning parameters:
## 
##   cp    Accuracy  Kappa  Accuracy SD  Kappa SD
##   0.04  0.5       0.4    0.02         0.02    
##   0.06  0.5       0.3    0.06         0.1     
##   0.1   0.3       0.07   0.04         0.07    
## 
## Accuracy was used to select the optimal model using  the largest value.
## The final value used for the model was cp = 0.04.
</code></pre>

<h3>
<a name="user-content-support-vector-machine-linear-kernel" class="anchor" href="#support-vector-machine-linear-kernel" aria-hidden="true"><span class="octicon octicon-link"></span></a>Support Vector Machine (linear kernel)</h3>

<div class="highlight highlight-r"><pre><span class="kp">set.seed</span><span class="p">(</span><span class="m">157885</span><span class="p">)</span>
model.svml <span class="o">&lt;-</span> train<span class="p">(</span>classe <span class="o">~</span> <span class="m">.</span><span class="p">,</span> data <span class="o">=</span> training<span class="p">,</span> method <span class="o">=</span> <span class="s">"svmLinear"</span>
                    <span class="p">,</span>trControl <span class="o">=</span> trControl<span class="p">,</span> preProcess <span class="o">=</span> <span class="kt">c</span><span class="p">(</span><span class="s">"center"</span><span class="p">,</span><span class="s">"scale"</span><span class="p">)</span>
<span class="p">)</span>
<span class="kp">print</span><span class="p">(</span>model.svml<span class="p">)</span>
</pre></div>

<pre><code>## Support Vector Machines with Linear Kernel 
## 
## 13737 samples
##    52 predictors
##     5 classes: 'A', 'B', 'C', 'D', 'E' 
## 
## Pre-processing: centered, scaled 
## Resampling: Cross-Validated (5 fold) 
## 
## Summary of sample sizes: 10989, 10991, 10989, 10990, 10989 
## 
## Resampling results
## 
##   Accuracy  Kappa  Accuracy SD  Kappa SD
##   0.8       0.7    0.008        0.01    
## 
## Tuning parameter 'C' was held constant at a value of 1
## 
</code></pre>

<h3>
<a name="user-content-support-vector-machine-radial-kernel" class="anchor" href="#support-vector-machine-radial-kernel" aria-hidden="true"><span class="octicon octicon-link"></span></a>Support Vector Machine (radial kernel)</h3>

<div class="highlight highlight-r"><pre><span class="kp">set.seed</span><span class="p">(</span><span class="m">157885</span><span class="p">)</span>
model.svmr <span class="o">&lt;-</span> train<span class="p">(</span>classe <span class="o">~</span> <span class="m">.</span><span class="p">,</span> data <span class="o">=</span> training<span class="p">,</span> method <span class="o">=</span> <span class="s">"svmRadial"</span>
                    <span class="p">,</span>trControl <span class="o">=</span> trControl<span class="p">,</span> preProcess <span class="o">=</span> <span class="kt">c</span><span class="p">(</span><span class="s">"center"</span><span class="p">,</span><span class="s">"scale"</span><span class="p">)</span>
<span class="p">)</span>
<span class="kp">print</span><span class="p">(</span>model.svmr<span class="p">)</span>
</pre></div>

<pre><code>## Support Vector Machines with Radial Basis Function Kernel 
## 
## 13737 samples
##    52 predictors
##     5 classes: 'A', 'B', 'C', 'D', 'E' 
## 
## Pre-processing: centered, scaled 
## Resampling: Cross-Validated (5 fold) 
## 
## Summary of sample sizes: 10989, 10991, 10989, 10990, 10989 
## 
## Resampling results across tuning parameters:
## 
##   C    Accuracy  Kappa  Accuracy SD  Kappa SD
##   0.2  0.9       0.8    0.008        0.01    
##   0.5  0.9       0.9    0.007        0.009   
##   1    0.9       0.9    0.006        0.007   
## 
## Tuning parameter 'sigma' was held constant at a value of 0.01251
## Accuracy was used to select the optimal model using  the largest value.
## The final values used for the model were sigma = 0.01 and C = 1.
</code></pre>

<h3>
<a name="user-content-random-forrests" class="anchor" href="#random-forrests" aria-hidden="true"><span class="octicon octicon-link"></span></a>Random Forrests</h3>

<div class="highlight highlight-r"><pre><span class="kp">set.seed</span><span class="p">(</span><span class="m">157885</span><span class="p">)</span>
model.rf <span class="o">&lt;-</span> train<span class="p">(</span>classe <span class="o">~</span> <span class="m">.</span><span class="p">,</span> data <span class="o">=</span> training<span class="p">,</span> method <span class="o">=</span> <span class="s">"rf"</span>
                  <span class="p">,</span>trControl <span class="o">=</span> trControl<span class="p">,</span> preProcess <span class="o">=</span> <span class="kt">c</span><span class="p">(</span><span class="s">"center"</span><span class="p">,</span><span class="s">"scale"</span><span class="p">)</span>
<span class="p">)</span>
<span class="kp">print</span><span class="p">(</span>model.rf<span class="p">)</span>
</pre></div>

<pre><code>## Random Forest 
## 
## 13737 samples
##    52 predictors
##     5 classes: 'A', 'B', 'C', 'D', 'E' 
## 
## Pre-processing: centered, scaled 
## Resampling: Cross-Validated (5 fold) 
## 
## Summary of sample sizes: 10989, 10991, 10989, 10990, 10989 
## 
## Resampling results across tuning parameters:
## 
##   mtry  Accuracy  Kappa  Accuracy SD  Kappa SD
##   2     1         1      0.003        0.004   
##   30    1         1      0.003        0.004   
##   50    1         1      0.003        0.003   
## 
## Accuracy was used to select the optimal model using  the largest value.
## The final value used for the model was mtry = 27.
</code></pre>

<h2>
<a name="user-content-model-selection" class="anchor" href="#model-selection" aria-hidden="true"><span class="octicon octicon-link"></span></a>Model Selection</h2>

<p>Finally the accuracy of the five models is compared:</p>

<div class="highlight highlight-r"><pre>resamps <span class="o">&lt;-</span> resamples<span class="p">(</span><span class="kt">list</span><span class="p">(</span>model.glm<span class="p">,</span> model.rpart<span class="p">,</span> model.svml<span class="p">,</span> model.svmr<span class="p">,</span> model.rf<span class="p">)</span>
                     <span class="p">,</span>modelNames <span class="o">=</span> <span class="kt">c</span><span class="p">(</span><span class="s">"Linear Model"</span>
                                    <span class="p">,</span><span class="s">"Decision Tree"</span>
                                    <span class="p">,</span><span class="s">"SVM (linear)"</span>
                                    <span class="p">,</span><span class="s">"SVM (radial)"</span>
                                    <span class="p">,</span><span class="s">"Random Forest"</span><span class="p">))</span>
trellis.par.set<span class="p">(</span>caretTheme<span class="p">())</span>
dotplot<span class="p">(</span>resamps<span class="p">,</span> metric <span class="o">=</span> <span class="s">"Accuracy"</span><span class="p">)</span>
</pre></div>

<p><a href="/McReyar/PredMachLearn_CourseProject/blob/gh-pages/figure/modsel.png" target="_blank"><img src="/McReyar/PredMachLearn_CourseProject/raw/gh-pages/figure/modsel.png" alt="plot of chunk modsel" style="max-width:100%;"></a> 
As can be seen, Random Forest has by far the highest accuary (99.11%). With so much more accuracy a loss of interpretability seems to be acceptable. Further optimization by model stacking seems not to be worth the effort.</p>

<h2>
<a name="user-content-final-model" class="anchor" href="#final-model" aria-hidden="true"><span class="octicon octicon-link"></span></a>Final Model</h2>

<p>With the best model the activity of the test data is predicted and compared with the real activity.</p>

<div class="highlight highlight-r"><pre>confMat <span class="o">&lt;-</span> confusionMatrix<span class="p">(</span>predict<span class="p">(</span>model.rf<span class="p">,</span> newdata<span class="o">=</span>testing<span class="p">),</span> testing<span class="o">$</span>classe<span class="p">)</span>
<span class="kp">print</span><span class="p">(</span>confMat<span class="p">)</span>
</pre></div>

<pre><code>## Confusion Matrix and Statistics
## 
##           Reference
## Prediction    A    B    C    D    E
##          A 1672   12    0    0    0
##          B    1 1126    7    1    0
##          C    0    1 1018   16    0
##          D    0    0    1  946    2
##          E    1    0    0    1 1080
## 
## Overall Statistics
##                                        
##                Accuracy : 0.993        
##                  95% CI : (0.99, 0.995)
##     No Information Rate : 0.284        
##     P-Value [Acc &gt; NIR] : &lt;2e-16       
##                                        
##                   Kappa : 0.991        
##  Mcnemar's Test P-Value : NA           
## 
## Statistics by Class:
## 
##                      Class: A Class: B Class: C Class: D Class: E
## Sensitivity             0.999    0.989    0.992    0.981    0.998
## Specificity             0.997    0.998    0.997    0.999    1.000
## Pos Pred Value          0.993    0.992    0.984    0.997    0.998
## Neg Pred Value          1.000    0.997    0.998    0.996    1.000
## Prevalence              0.284    0.194    0.174    0.164    0.184
## Detection Rate          0.284    0.191    0.173    0.161    0.184
## Detection Prevalence    0.286    0.193    0.176    0.161    0.184
## Balanced Accuracy       0.998    0.993    0.994    0.990    0.999
</code></pre>

<p>Similar to the accuracy obtained by cross validation, the out of sample accuracy is also very high (99.27)%. We would expect about 0.73% classification errors.</p>

<p>As these results confirm the findings based on cross validation, the final model is built with random forest and the parameters of the best model on the whole dataset.</p>

<div class="highlight highlight-r"><pre>finalModel <span class="o">&lt;-</span> train<span class="p">(</span>classe <span class="o">~</span> <span class="m">.</span><span class="p">,</span> data <span class="o">=</span> pml<span class="p">,</span> method <span class="o">=</span> <span class="s">"rf"</span>
                   <span class="p">,</span>preProcess <span class="o">=</span> <span class="kt">c</span><span class="p">(</span><span class="s">"center"</span><span class="p">,</span><span class="s">"scale"</span><span class="p">)</span>
                   <span class="p">,</span>trControl  <span class="o">=</span> trainControl<span class="p">(</span>method <span class="o">=</span> <span class="s">"none"</span><span class="p">)</span>
                   <span class="p">,</span>tuneGrid   <span class="o">=</span> model.rf<span class="o">$</span>bestTune
                   <span class="p">)</span>
</pre></div>

<p>This model is used to make a prediction on the 20 real-world cases for which the real activity is not known.</p>

<div class="highlight highlight-r"><pre>kable<span class="p">(</span><span class="kt">data.frame</span><span class="p">(</span>Row <span class="o">=</span> <span class="kp">row.names</span><span class="p">(</span>predict<span class="p">)</span>
                <span class="p">,</span>Prediction <span class="o">=</span> predict<span class="p">(</span>finalModel<span class="p">,</span> newdata<span class="o">=</span>predict<span class="p">)))</span>
</pre></div>

<table>
<thead><tr>
<th align="left">Row</th>
<th align="left">Prediction</th>
</tr></thead>
<tbody>
<tr>
<td align="left">1</td>
<td align="left">B</td>
</tr>
<tr>
<td align="left">2</td>
<td align="left">A</td>
</tr>
<tr>
<td align="left">3</td>
<td align="left">B</td>
</tr>
<tr>
<td align="left">4</td>
<td align="left">A</td>
</tr>
<tr>
<td align="left">5</td>
<td align="left">A</td>
</tr>
<tr>
<td align="left">6</td>
<td align="left">E</td>
</tr>
<tr>
<td align="left">7</td>
<td align="left">D</td>
</tr>
<tr>
<td align="left">8</td>
<td align="left">B</td>
</tr>
<tr>
<td align="left">9</td>
<td align="left">A</td>
</tr>
<tr>
<td align="left">10</td>
<td align="left">A</td>
</tr>
<tr>
<td align="left">11</td>
<td align="left">B</td>
</tr>
<tr>
<td align="left">12</td>
<td align="left">C</td>
</tr>
<tr>
<td align="left">13</td>
<td align="left">B</td>
</tr>
<tr>
<td align="left">14</td>
<td align="left">A</td>
</tr>
<tr>
<td align="left">15</td>
<td align="left">E</td>
</tr>
<tr>
<td align="left">16</td>
<td align="left">E</td>
</tr>
<tr>
<td align="left">17</td>
<td align="left">A</td>
</tr>
<tr>
<td align="left">18</td>
<td align="left">B</td>
</tr>
<tr>
<td align="left">19</td>
<td align="left">B</td>
</tr>
<tr>
<td align="left">20</td>
<td align="left">B</td>
</tr>
</tbody>
</table><h1>
<a name="user-content-references" class="anchor" href="#references" aria-hidden="true"><span class="octicon octicon-link"></span></a>References</h1>

<p>[^1]: Velloso, E.; Bulling, A.; Gellersen, H.; Ugulino, W.; Fuks, H. Qualitative Activity Recognition of Weight Lifting Exercises. Proceedings of 4th International Conference in Cooperation with SIGCHI (Augmented Human '13) . Stuttgart, Germany: ACM SIGCHI, 2013.</p></article>
  </div>

  </div>
</div>

<a href="#jump-to-line" rel="facebox[.linejump]" data-hotkey="l" style="display:none">Jump to Line</a>
<div id="jump-to-line" style="display:none">
  <form accept-charset="UTF-8" class="js-jump-to-line-form">
    <input class="linejump-input js-jump-to-line-field" type="text" placeholder="Jump to line&hellip;" autofocus>
    <button type="submit" class="button">Go</button>
  </form>
</div>

        </div>

      </div><!-- /.repo-container -->
      <div class="modal-backdrop"></div>
    </div><!-- /.container -->
  </div><!-- /.site -->


    </div><!-- /.wrapper -->

      <div class="container">
  <div class="site-footer">
    <ul class="site-footer-links right">
      <li><a href="https://status.github.com/">Status</a></li>
      <li><a href="http://developer.github.com">API</a></li>
      <li><a href="http://training.github.com">Training</a></li>
      <li><a href="http://shop.github.com">Shop</a></li>
      <li><a href="/blog">Blog</a></li>
      <li><a href="/about">About</a></li>

    </ul>

    <a href="/" aria-label="Homepage">
      <span class="mega-octicon octicon-mark-github" title="GitHub"></span>
    </a>

    <ul class="site-footer-links">
      <li>&copy; 2014 <span title="0.03419s from github-fe128-cp1-prd.iad.github.net">GitHub</span>, Inc.</li>
        <li><a href="/site/terms">Terms</a></li>
        <li><a href="/site/privacy">Privacy</a></li>
        <li><a href="/security">Security</a></li>
        <li><a href="/contact">Contact</a></li>
    </ul>
  </div><!-- /.site-footer -->
</div><!-- /.container -->


    <div class="fullscreen-overlay js-fullscreen-overlay" id="fullscreen_overlay">
  <div class="fullscreen-container js-suggester-container">
    <div class="textarea-wrap">
      <textarea name="fullscreen-contents" id="fullscreen-contents" class="fullscreen-contents js-fullscreen-contents js-suggester-field" placeholder=""></textarea>
    </div>
  </div>
  <div class="fullscreen-sidebar">
    <a href="#" class="exit-fullscreen js-exit-fullscreen tooltipped tooltipped-w" aria-label="Exit Zen Mode">
      <span class="mega-octicon octicon-screen-normal"></span>
    </a>
    <a href="#" class="theme-switcher js-theme-switcher tooltipped tooltipped-w"
      aria-label="Switch themes">
      <span class="octicon octicon-color-mode"></span>
    </a>
  </div>
</div>



    <div id="ajax-error-message" class="flash flash-error">
      <span class="octicon octicon-alert"></span>
      <a href="#" class="octicon octicon-x close js-ajax-error-dismiss" aria-label="Dismiss error"></a>
      Something went wrong with that request. Please try again.
    </div>


      <script crossorigin="anonymous" src="https://assets-cdn.github.com/assets/frameworks-12d5fda141e78e513749dddbc56445fe172cbd9a.js" type="text/javascript"></script>
      <script async="async" crossorigin="anonymous" src="https://assets-cdn.github.com/assets/github-a61187924f7160c9ea470f937aa5fb3d3dc74191.js" type="text/javascript"></script>
      
      
        <script async src="https://www.google-analytics.com/analytics.js"></script>
  </body>
</html>

