


<!DOCTYPE html>
<html lang="en" class=" is-copy-enabled">
  <head prefix="og: http://ogp.me/ns# fb: http://ogp.me/ns/fb# object: http://ogp.me/ns/object# article: http://ogp.me/ns/article# profile: http://ogp.me/ns/profile#">
    <meta charset='utf-8'>
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta http-equiv="Content-Language" content="en">
    <meta name="viewport" content="width=1020">
    
    
    <title>RepData_PeerAssessment1/PA1_template.md at master · Xiaodan/RepData_PeerAssessment1</title>
    <link rel="search" type="application/opensearchdescription+xml" href="/opensearch.xml" title="GitHub">
    <link rel="fluid-icon" href="https://github.com/fluidicon.png" title="GitHub">
    <link rel="apple-touch-icon" sizes="57x57" href="/apple-touch-icon-114.png">
    <link rel="apple-touch-icon" sizes="114x114" href="/apple-touch-icon-114.png">
    <link rel="apple-touch-icon" sizes="72x72" href="/apple-touch-icon-144.png">
    <link rel="apple-touch-icon" sizes="144x144" href="/apple-touch-icon-144.png">
    <meta property="fb:app_id" content="1401488693436528">

      <meta content="@github" name="twitter:site" /><meta content="summary" name="twitter:card" /><meta content="Xiaodan/RepData_PeerAssessment1" name="twitter:title" /><meta content="RepData_PeerAssessment1 - Peer Assessment 1 for Reproducible Research" name="twitter:description" /><meta content="https://avatars3.githubusercontent.com/u/1871047?v=3&amp;s=400" name="twitter:image:src" />
      <meta content="GitHub" property="og:site_name" /><meta content="object" property="og:type" /><meta content="https://avatars3.githubusercontent.com/u/1871047?v=3&amp;s=400" property="og:image" /><meta content="Xiaodan/RepData_PeerAssessment1" property="og:title" /><meta content="https://github.com/Xiaodan/RepData_PeerAssessment1" property="og:url" /><meta content="RepData_PeerAssessment1 - Peer Assessment 1 for Reproducible Research" property="og:description" />
      <meta name="browser-stats-url" content="https://api.github.com/_private/browser/stats">
    <meta name="browser-errors-url" content="https://api.github.com/_private/browser/errors">
    <link rel="assets" href="https://assets-cdn.github.com/">
    <link rel="web-socket" href="wss://live.github.com/_sockets/MTAxODkyNDk6MmIxY2U1OWUzN2M3OTE1OGJjMmIyYjYwNDdlNzA4YzY6YmE5ZWNjZTZhMDFjMzA2Yjg5YTdiNGEwOWQ3YTc2YTVmNGFiNWUxNjQwZGZlMmRlNTgwYWFkN2E5NDFjMGRjYw==--1f219db5e421cf604e1e65ec482d5b3aefabe174">
    <meta name="pjax-timeout" content="1000">
    <link rel="sudo-modal" href="/sessions/sudo_modal">

    <meta name="msapplication-TileImage" content="/windows-tile.png">
    <meta name="msapplication-TileColor" content="#ffffff">
    <meta name="selected-link" value="repo_source" data-pjax-transient>

        <meta name="google-analytics" content="UA-3769691-2">

    <meta content="collector.githubapp.com" name="octolytics-host" /><meta content="collector-cdn.github.com" name="octolytics-script-host" /><meta content="github" name="octolytics-app-id" /><meta content="6C5D4F92:7C78:2CBD645:55D11DE8" name="octolytics-dimension-request_id" /><meta content="10189249" name="octolytics-actor-id" /><meta content="FloraC" name="octolytics-actor-login" /><meta content="2f187ae2b303f0596c08b3336012bcc46218e6a83ef13380dc9c75bcd8894bbf" name="octolytics-actor-hash" />
    
    <meta content="Rails, view, blob#show" data-pjax-transient="true" name="analytics-event" />
    <meta class="js-ga-set" name="dimension1" content="Logged In">
      <meta class="js-ga-set" name="dimension4" content="Current repo nav">
    <meta name="is-dotcom" content="true">
        <meta name="hostname" content="github.com">
    <meta name="user-login" content="FloraC">

      <link rel="icon" sizes="any" mask href="https://assets-cdn.github.com/pinned-octocat.svg">
      <meta name="theme-color" content="#4078c0">
      <link rel="icon" type="image/x-icon" href="https://assets-cdn.github.com/favicon.ico">

    <!-- </textarea> --><!-- '"` --><meta content="authenticity_token" name="csrf-param" />
<meta content="EFZiPx/bzoNsYxUGSgaCQCFnMSoNtRmjd+VYLLCEGJPjcQdE/NmJwnae/kki7aY2ne2jnPbHdKPPaJiJBs6qMQ==" name="csrf-token" />
    

    <link crossorigin="anonymous" href="https://assets-cdn.github.com/assets/github/index-78350b39bf13714f4b06a2153e5374de01bc939bfa60ec9bdb34dbb2032dda4b.css" media="all" rel="stylesheet" />
    <link crossorigin="anonymous" href="https://assets-cdn.github.com/assets/github2/index-fe5622bab39e70fefc28ebe1ea2e8fa620c0c026df4a6b089aac3bf495d3463e.css" media="all" rel="stylesheet" />
    
    


    <meta http-equiv="x-pjax-version" content="a26d7fe411f453e1f88034a366ff5217">

      
  <meta name="description" content="RepData_PeerAssessment1 - Peer Assessment 1 for Reproducible Research">
  <meta name="go-import" content="github.com/Xiaodan/RepData_PeerAssessment1 git https://github.com/Xiaodan/RepData_PeerAssessment1.git">

  <meta content="1871047" name="octolytics-dimension-user_id" /><meta content="Xiaodan" name="octolytics-dimension-user_login" /><meta content="21998662" name="octolytics-dimension-repository_id" /><meta content="Xiaodan/RepData_PeerAssessment1" name="octolytics-dimension-repository_nwo" /><meta content="true" name="octolytics-dimension-repository_public" /><meta content="true" name="octolytics-dimension-repository_is_fork" /><meta content="16709733" name="octolytics-dimension-repository_parent_id" /><meta content="rdpeng/RepData_PeerAssessment1" name="octolytics-dimension-repository_parent_nwo" /><meta content="16709733" name="octolytics-dimension-repository_network_root_id" /><meta content="rdpeng/RepData_PeerAssessment1" name="octolytics-dimension-repository_network_root_nwo" />
  <link href="https://github.com/Xiaodan/RepData_PeerAssessment1/commits/master.atom" rel="alternate" title="Recent Commits to RepData_PeerAssessment1:master" type="application/atom+xml">

  </head>


  <body class="logged_in  env-production windows vis-public fork page-blob">
    <a href="#start-of-content" tabindex="1" class="accessibility-aid js-skip-to-content">Skip to content</a>
    <div class="wrapper">
      
      
      



        <div class="header header-logged-in true" role="banner">
  <div class="container clearfix">

    <a class="header-logo-invertocat" href="https://github.com/" data-hotkey="g d" aria-label="Homepage" data-ga-click="Header, go to dashboard, icon:logo">
  <span class="mega-octicon octicon-mark-github"></span>
</a>


      <div class="site-search repo-scope js-site-search" role="search">
          <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="/Xiaodan/RepData_PeerAssessment1/search" class="js-site-search-form" data-global-search-url="/search" data-repo-search-url="/Xiaodan/RepData_PeerAssessment1/search" method="get"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /></div>
  <label class="js-chromeless-input-container form-control">
    <div class="scope-badge">This repository</div>
    <input type="text"
      class="js-site-search-focus js-site-search-field is-clearable chromeless-input"
      data-hotkey="s"
      name="q"
      placeholder="Search"
      aria-label="Search this repository"
      data-global-scope-placeholder="Search GitHub"
      data-repo-scope-placeholder="Search"
      tabindex="1"
      autocapitalize="off">
  </label>
</form>
      </div>

      <ul class="header-nav left" role="navigation">
        <li class="header-nav-item">
          <a href="/pulls" class="js-selected-navigation-item header-nav-link" data-ga-click="Header, click, Nav menu - item:pulls context:user" data-hotkey="g p" data-selected-links="/pulls /pulls/assigned /pulls/mentioned /pulls">
            Pull requests
</a>        </li>
        <li class="header-nav-item">
          <a href="/issues" class="js-selected-navigation-item header-nav-link" data-ga-click="Header, click, Nav menu - item:issues context:user" data-hotkey="g i" data-selected-links="/issues /issues/assigned /issues/mentioned /issues">
            Issues
</a>        </li>
          <li class="header-nav-item">
            <a class="header-nav-link" href="https://gist.github.com/" data-ga-click="Header, go to gist, text:gist">Gist</a>
          </li>
      </ul>

    
<ul class="header-nav user-nav right" id="user-links">
  <li class="header-nav-item">
      <span class="js-socket-channel js-updatable-content"
        data-channel="notification-changed:FloraC"
        data-url="/notifications/header">
      <a href="/notifications" aria-label="You have no unread notifications" class="header-nav-link notification-indicator tooltipped tooltipped-s" data-ga-click="Header, go to notifications, icon:read" data-hotkey="g n">
          <span class="mail-status all-read"></span>
          <span class="octicon octicon-inbox"></span>
</a>  </span>

  </li>

  <li class="header-nav-item dropdown js-menu-container">
    <a class="header-nav-link tooltipped tooltipped-s js-menu-target" href="/new"
       aria-label="Create new…"
       data-ga-click="Header, create new, icon:add">
      <span class="octicon octicon-plus left"></span>
      <span class="dropdown-caret"></span>
    </a>

    <div class="dropdown-menu-content js-menu-content">
      <ul class="dropdown-menu dropdown-menu-sw">
        
<a class="dropdown-item" href="/new" data-ga-click="Header, create new repository">
  New repository
</a>


  <a class="dropdown-item" href="/organizations/new" data-ga-click="Header, create new organization">
    New organization
  </a>




      </ul>
    </div>
  </li>

  <li class="header-nav-item dropdown js-menu-container">
    <a class="header-nav-link name tooltipped tooltipped-s js-menu-target" href="/FloraC"
       aria-label="View profile and more"
       data-ga-click="Header, show menu, icon:avatar">
      <img alt="@FloraC" class="avatar" height="20" src="https://avatars0.githubusercontent.com/u/10189249?v=3&amp;s=40" width="20" />
      <span class="dropdown-caret"></span>
    </a>

    <div class="dropdown-menu-content js-menu-content">
      <div class="dropdown-menu dropdown-menu-sw">
        <div class="dropdown-header header-nav-current-user css-truncate">
          Signed in as <strong class="css-truncate-target">FloraC</strong>
        </div>
        <div class="dropdown-divider"></div>

        <a class="dropdown-item" href="/FloraC" data-ga-click="Header, go to profile, text:your profile">
          Your profile
        </a>
        <a class="dropdown-item" href="/stars" data-ga-click="Header, go to starred repos, text:your stars">
          Your stars
        </a>
        <a class="dropdown-item" href="/explore" data-ga-click="Header, go to explore, text:explore">
          Explore
        </a>
        <a class="dropdown-item" href="https://help.github.com" data-ga-click="Header, go to help, text:help">
          Help
        </a>
        <div class="dropdown-divider"></div>

        <a class="dropdown-item" href="/settings/profile" data-ga-click="Header, go to settings, icon:settings">
          Settings
        </a>

        <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="/logout" class="logout-form" data-form-nonce="4decf78111106bf20c7da0ccb4a1283e2db706cf" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="ns+mfBLF4PT5SfEidthcskGTQ7DnevJ/EPnKz7SVOdpUGIToUggHFzF/PgyDXsKuUZx/j3tQ8+VFeQ7rUYsQPw==" /></div>
          <button class="dropdown-item dropdown-signout" data-ga-click="Header, sign out, icon:logout">
            Sign out
          </button>
</form>      </div>
    </div>
  </li>
</ul>


    
  </div>
</div>

        

        


      <div id="start-of-content" class="accessibility-aid"></div>
          <div class="site" itemscope itemtype="http://schema.org/WebPage">
    <div id="js-flash-container">
      
    </div>
    <div class="pagehead repohead instapaper_ignore readability-menu ">
      <div class="container">

        <div class="clearfix">
          
<ul class="pagehead-actions">

  <li>
      <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="/notifications/subscribe" class="js-social-container" data-autosubmit="true" data-form-nonce="4decf78111106bf20c7da0ccb4a1283e2db706cf" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="8HL6bOHLgGYGdQbpvg93VQehx9tUsciNW50RJc7zyMajbxkA1bm+oAEWJFVbsa90OpvNm6KwMK4yL3wxJIujSw==" /></div>    <input id="repository_id" name="repository_id" type="hidden" value="21998662" />

      <div class="select-menu js-menu-container js-select-menu">
        <a href="/Xiaodan/RepData_PeerAssessment1/subscription"
          class="btn btn-sm btn-with-count select-menu-button js-menu-target" role="button" tabindex="0" aria-haspopup="true"
          data-ga-click="Repository, click Watch settings, action:blob#show">
          <span class="js-select-button">
            <span class="octicon octicon-eye"></span>
            Watch
          </span>
        </a>
        <a class="social-count js-social-count" href="/Xiaodan/RepData_PeerAssessment1/watchers">
          0
        </a>

        <div class="select-menu-modal-holder">
          <div class="select-menu-modal subscription-menu-modal js-menu-content" aria-hidden="true">
            <div class="select-menu-header">
              <span class="select-menu-title">Notifications</span>
              <span class="octicon octicon-x js-menu-close" role="button" aria-label="Close"></span>
            </div>

            <div class="select-menu-list js-navigation-container" role="menu">

              <div class="select-menu-item js-navigation-item selected" role="menuitem" tabindex="0">
                <span class="select-menu-item-icon octicon octicon-check"></span>
                <div class="select-menu-item-text">
                  <input checked="checked" id="do_included" name="do" type="radio" value="included" />
                  <span class="select-menu-item-heading">Not watching</span>
                  <span class="description">Be notified when participating or @mentioned.</span>
                  <span class="js-select-button-text hidden-select-button-text">
                    <span class="octicon octicon-eye"></span>
                    Watch
                  </span>
                </div>
              </div>

              <div class="select-menu-item js-navigation-item " role="menuitem" tabindex="0">
                <span class="select-menu-item-icon octicon octicon octicon-check"></span>
                <div class="select-menu-item-text">
                  <input id="do_subscribed" name="do" type="radio" value="subscribed" />
                  <span class="select-menu-item-heading">Watching</span>
                  <span class="description">Be notified of all conversations.</span>
                  <span class="js-select-button-text hidden-select-button-text">
                    <span class="octicon octicon-eye"></span>
                    Unwatch
                  </span>
                </div>
              </div>

              <div class="select-menu-item js-navigation-item " role="menuitem" tabindex="0">
                <span class="select-menu-item-icon octicon octicon-check"></span>
                <div class="select-menu-item-text">
                  <input id="do_ignore" name="do" type="radio" value="ignore" />
                  <span class="select-menu-item-heading">Ignoring</span>
                  <span class="description">Never be notified.</span>
                  <span class="js-select-button-text hidden-select-button-text">
                    <span class="octicon octicon-mute"></span>
                    Stop ignoring
                  </span>
                </div>
              </div>

            </div>

          </div>
        </div>
      </div>
</form>
  </li>

  <li>
    
  <div class="js-toggler-container js-social-container starring-container ">

    <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="/Xiaodan/RepData_PeerAssessment1/unstar" class="js-toggler-form starred js-unstar-button" data-form-nonce="4decf78111106bf20c7da0ccb4a1283e2db706cf" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="WYdTRaNf2p/QZ0QQavf8FjexcMqCJGjsvvtbHgWsr6yk4MwbGDBw3U2atam1HP+4jtW0wx6qU80LFXqfyk65VQ==" /></div>
      <button
        class="btn btn-sm btn-with-count js-toggler-target"
        aria-label="Unstar this repository" title="Unstar Xiaodan/RepData_PeerAssessment1"
        data-ga-click="Repository, click unstar button, action:blob#show; text:Unstar">
        <span class="octicon octicon-star"></span>
        Unstar
      </button>
        <a class="social-count js-social-count" href="/Xiaodan/RepData_PeerAssessment1/stargazers">
          0
        </a>
</form>
    <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="/Xiaodan/RepData_PeerAssessment1/star" class="js-toggler-form unstarred js-star-button" data-form-nonce="4decf78111106bf20c7da0ccb4a1283e2db706cf" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="MtBPvp6jbwkCEOTT48w26EW12ZtkFggR1IjeV7jNqFJ8WkHCeVwSNo8QffyaTixATMi1H9h7unux//iLBiQmMg==" /></div>
      <button
        class="btn btn-sm btn-with-count js-toggler-target"
        aria-label="Star this repository" title="Star Xiaodan/RepData_PeerAssessment1"
        data-ga-click="Repository, click star button, action:blob#show; text:Star">
        <span class="octicon octicon-star"></span>
        Star
      </button>
        <a class="social-count js-social-count" href="/Xiaodan/RepData_PeerAssessment1/stargazers">
          0
        </a>
</form>  </div>

  </li>

        <li>
          <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="/Xiaodan/RepData_PeerAssessment1/fork" data-form-nonce="4decf78111106bf20c7da0ccb4a1283e2db706cf" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="KUQ20YIrsokYUMqzozbpkCcRd5uuRHuVtVO78LxCaI8VWb7d9h62gpTX/8gcxOyqRfqx/hTmjIdH5wf8Hkd/0g==" /></div>
            <button
                type="submit"
                class="btn btn-sm btn-with-count"
                data-ga-click="Repository, show fork modal, action:blob#show; text:Fork"
                title="Fork your own copy of Xiaodan/RepData_PeerAssessment1 to your account"
                aria-label="Fork your own copy of Xiaodan/RepData_PeerAssessment1 to your account">
              <span class="octicon octicon-repo-forked"></span>
              Fork
            </button>
            <a href="/Xiaodan/RepData_PeerAssessment1/network" class="social-count">17,463</a>
</form>        </li>

</ul>

          <h1 itemscope itemtype="http://data-vocabulary.org/Breadcrumb" class="entry-title public ">
            <span class="mega-octicon octicon-repo-forked"></span>
            <span class="author"><a href="/Xiaodan" class="url fn" itemprop="url" rel="author"><span itemprop="title">Xiaodan</span></a></span><!--
         --><span class="path-divider">/</span><!--
         --><strong><a href="/Xiaodan/RepData_PeerAssessment1" data-pjax="#js-repo-pjax-container">RepData_PeerAssessment1</a></strong>

            <span class="page-context-loader">
              <img alt="" height="16" src="https://assets-cdn.github.com/images/spinners/octocat-spinner-32.gif" width="16" />
            </span>

              <span class="fork-flag">
                <span class="text">forked from <a href="/rdpeng/RepData_PeerAssessment1">rdpeng/RepData_PeerAssessment1</a></span>
              </span>
          </h1>
        </div>

      </div>
    </div>

      <div class="container">
        <div class="repository-with-sidebar repo-container new-discussion-timeline ">
          <div class="repository-sidebar clearfix">
              

<nav class="sunken-menu repo-nav js-repo-nav js-sidenav-container-pjax js-octicon-loaders"
     role="navigation"
     data-pjax="#js-repo-pjax-container"
     data-issue-count-url="/Xiaodan/RepData_PeerAssessment1/issues/counts">
  <ul class="sunken-menu-group">
    <li class="tooltipped tooltipped-w" aria-label="Code">
      <a href="/Xiaodan/RepData_PeerAssessment1" aria-label="Code" aria-selected="true" class="js-selected-navigation-item selected sunken-menu-item" data-hotkey="g c" data-selected-links="repo_source repo_downloads repo_commits repo_releases repo_tags repo_branches /Xiaodan/RepData_PeerAssessment1">
        <span class="octicon octicon-code"></span> <span class="full-word">Code</span>
        <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/images/spinners/octocat-spinner-32.gif" width="16" />
</a>    </li>


    <li class="tooltipped tooltipped-w" aria-label="Pull requests">
      <a href="/Xiaodan/RepData_PeerAssessment1/pulls" aria-label="Pull requests" class="js-selected-navigation-item sunken-menu-item" data-hotkey="g p" data-selected-links="repo_pulls /Xiaodan/RepData_PeerAssessment1/pulls">
          <span class="octicon octicon-git-pull-request"></span> <span class="full-word">Pull requests</span>
          <span class="js-pull-replace-counter"></span>
          <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/images/spinners/octocat-spinner-32.gif" width="16" />
</a>    </li>

      <li class="tooltipped tooltipped-w" aria-label="Wiki">
        <a href="/Xiaodan/RepData_PeerAssessment1/wiki" aria-label="Wiki" class="js-selected-navigation-item sunken-menu-item" data-hotkey="g w" data-selected-links="repo_wiki /Xiaodan/RepData_PeerAssessment1/wiki">
          <span class="octicon octicon-book"></span> <span class="full-word">Wiki</span>
          <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/images/spinners/octocat-spinner-32.gif" width="16" />
</a>      </li>
  </ul>
  <div class="sunken-menu-separator"></div>
  <ul class="sunken-menu-group">

    <li class="tooltipped tooltipped-w" aria-label="Pulse">
      <a href="/Xiaodan/RepData_PeerAssessment1/pulse" aria-label="Pulse" class="js-selected-navigation-item sunken-menu-item" data-selected-links="pulse /Xiaodan/RepData_PeerAssessment1/pulse">
        <span class="octicon octicon-pulse"></span> <span class="full-word">Pulse</span>
        <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/images/spinners/octocat-spinner-32.gif" width="16" />
</a>    </li>

    <li class="tooltipped tooltipped-w" aria-label="Graphs">
      <a href="/Xiaodan/RepData_PeerAssessment1/graphs" aria-label="Graphs" class="js-selected-navigation-item sunken-menu-item" data-selected-links="repo_graphs repo_contributors /Xiaodan/RepData_PeerAssessment1/graphs">
        <span class="octicon octicon-graph"></span> <span class="full-word">Graphs</span>
        <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/images/spinners/octocat-spinner-32.gif" width="16" />
</a>    </li>
  </ul>


</nav>

                <div class="only-with-full-nav">
                    
<div class="js-clone-url clone-url open"
  data-protocol-type="http">
  <h3><span class="text-emphasized">HTTPS</span> clone URL</h3>
  <div class="input-group js-zeroclipboard-container">
    <input type="text" class="input-mini input-monospace js-url-field js-zeroclipboard-target"
           value="https://github.com/Xiaodan/RepData_PeerAssessment1.git" readonly="readonly" aria-label="HTTPS clone URL">
    <span class="input-group-button">
      <button aria-label="Copy to clipboard" class="js-zeroclipboard btn btn-sm zeroclipboard-button tooltipped tooltipped-s" data-copied-hint="Copied!" type="button"><span class="octicon octicon-clippy"></span></button>
    </span>
  </div>
</div>

  
<div class="js-clone-url clone-url "
  data-protocol-type="ssh">
  <h3><span class="text-emphasized">SSH</span> clone URL</h3>
  <div class="input-group js-zeroclipboard-container">
    <input type="text" class="input-mini input-monospace js-url-field js-zeroclipboard-target"
           value="git@github.com:Xiaodan/RepData_PeerAssessment1.git" readonly="readonly" aria-label="SSH clone URL">
    <span class="input-group-button">
      <button aria-label="Copy to clipboard" class="js-zeroclipboard btn btn-sm zeroclipboard-button tooltipped tooltipped-s" data-copied-hint="Copied!" type="button"><span class="octicon octicon-clippy"></span></button>
    </span>
  </div>
</div>

  
<div class="js-clone-url clone-url "
  data-protocol-type="subversion">
  <h3><span class="text-emphasized">Subversion</span> checkout URL</h3>
  <div class="input-group js-zeroclipboard-container">
    <input type="text" class="input-mini input-monospace js-url-field js-zeroclipboard-target"
           value="https://github.com/Xiaodan/RepData_PeerAssessment1" readonly="readonly" aria-label="Subversion checkout URL">
    <span class="input-group-button">
      <button aria-label="Copy to clipboard" class="js-zeroclipboard btn btn-sm zeroclipboard-button tooltipped tooltipped-s" data-copied-hint="Copied!" type="button"><span class="octicon octicon-clippy"></span></button>
    </span>
  </div>
</div>



  <div class="clone-options">You can clone with
    <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="/users/set_protocol?protocol_selector=http&amp;protocol_type=clone" class="inline-form js-clone-selector-form is-enabled" data-form-nonce="4decf78111106bf20c7da0ccb4a1283e2db706cf" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="GWGAbgq262pr2Q2rx8mHYxnwvWFOzheSTo5kuJm9RSi71HT88awlILOD6d9qRLV6zR2o8BCKZQVpR36Cv0NhkQ==" /></div><button class="btn-link js-clone-selector" data-protocol="http" type="submit">HTTPS</button></form>, <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="/users/set_protocol?protocol_selector=ssh&amp;protocol_type=clone" class="inline-form js-clone-selector-form is-enabled" data-form-nonce="4decf78111106bf20c7da0ccb4a1283e2db706cf" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="E5p2TMm40PQGmJe89++/S3lsPAMQueCkMVlfkabIC9g6YZ5ohH1hoi6NJg1yYEYBVt1U91BTEry5geEqDoz0Pw==" /></div><button class="btn-link js-clone-selector" data-protocol="ssh" type="submit">SSH</button></form>, or <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="/users/set_protocol?protocol_selector=subversion&amp;protocol_type=clone" class="inline-form js-clone-selector-form is-enabled" data-form-nonce="4decf78111106bf20c7da0ccb4a1283e2db706cf" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="lwpIBcwNFOc6PnnXBXOcUlWi0kTq2mYoh3ZHMwg5W2yjVoFaBPo2RM/UlKoQAHmjw11gZ45dUioQKrP4l/huTw==" /></div><button class="btn-link js-clone-selector" data-protocol="subversion" type="submit">Subversion</button></form>.
    <a href="https://help.github.com/articles/which-remote-url-should-i-use" class="help tooltipped tooltipped-n" aria-label="Get help on which URL is right for you.">
      <span class="octicon octicon-question"></span>
    </a>
  </div>
    <a href="github-windows://openRepo/https://github.com/Xiaodan/RepData_PeerAssessment1" class="btn btn-sm sidebar-button" title="Save Xiaodan/RepData_PeerAssessment1 to your computer and use it in GitHub Desktop." aria-label="Save Xiaodan/RepData_PeerAssessment1 to your computer and use it in GitHub Desktop.">
      <span class="octicon octicon-desktop-download"></span>
      Clone in Desktop
    </a>

                  <a href="/Xiaodan/RepData_PeerAssessment1/archive/master.zip"
                     class="btn btn-sm sidebar-button"
                     aria-label="Download the contents of Xiaodan/RepData_PeerAssessment1 as a zip file"
                     title="Download the contents of Xiaodan/RepData_PeerAssessment1 as a zip file"
                     rel="nofollow">
                    <span class="octicon octicon-cloud-download"></span>
                    Download ZIP
                  </a>
                </div>
          </div>
          <div id="js-repo-pjax-container" class="repository-content context-loader-container" data-pjax-container>

            

<a href="/Xiaodan/RepData_PeerAssessment1/blob/6a1b0529f56defc984bd582b3726b8b65be78dcd/PA1_template.md" class="hidden js-permalink-shortcut" data-hotkey="y">Permalink</a>

<!-- blob contrib key: blob_contributors:v21:c72a48f7099193b253d12c3c4a14c63d -->

  <div class="file-navigation js-zeroclipboard-container">
    
<div class="select-menu js-menu-container js-select-menu left">
  <span class="btn btn-sm select-menu-button js-menu-target css-truncate" data-hotkey="w"
    data-ref="master"
    title="master"
    role="button" aria-label="Switch branches or tags" tabindex="0" aria-haspopup="true">
    <i>Branch:</i>
    <span class="js-select-button css-truncate-target">master</span>
  </span>

  <div class="select-menu-modal-holder js-menu-content js-navigation-container" data-pjax aria-hidden="true">

    <div class="select-menu-modal">
      <div class="select-menu-header">
        <span class="select-menu-title">Switch branches/tags</span>
        <span class="octicon octicon-x js-menu-close" role="button" aria-label="Close"></span>
      </div>

      <div class="select-menu-filters">
        <div class="select-menu-text-filter">
          <input type="text" aria-label="Filter branches/tags" id="context-commitish-filter-field" class="js-filterable-field js-navigation-enable" placeholder="Filter branches/tags">
        </div>
        <div class="select-menu-tabs">
          <ul>
            <li class="select-menu-tab">
              <a href="#" data-tab-filter="branches" data-filter-placeholder="Filter branches/tags" class="js-select-menu-tab" role="tab">Branches</a>
            </li>
            <li class="select-menu-tab">
              <a href="#" data-tab-filter="tags" data-filter-placeholder="Find a tag…" class="js-select-menu-tab" role="tab">Tags</a>
            </li>
          </ul>
        </div>
      </div>

      <div class="select-menu-list select-menu-tab-bucket js-select-menu-tab-bucket" data-tab-filter="branches" role="menu">

        <div data-filterable-for="context-commitish-filter-field" data-filterable-type="substring">


            <a class="select-menu-item js-navigation-item js-navigation-open selected"
               href="/Xiaodan/RepData_PeerAssessment1/blob/master/PA1_template.md"
               data-name="master"
               data-skip-pjax="true"
               rel="nofollow">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <span class="select-menu-item-text css-truncate-target" title="master">
                master
              </span>
            </a>
        </div>

          <div class="select-menu-no-results">Nothing to show</div>
      </div>

      <div class="select-menu-list select-menu-tab-bucket js-select-menu-tab-bucket" data-tab-filter="tags">
        <div data-filterable-for="context-commitish-filter-field" data-filterable-type="substring">


        </div>

        <div class="select-menu-no-results">Nothing to show</div>
      </div>

    </div>
  </div>
</div>

    <div class="btn-group right">
      <a href="/Xiaodan/RepData_PeerAssessment1/find/master"
            class="js-show-file-finder btn btn-sm empty-icon tooltipped tooltipped-nw"
            data-pjax
            data-hotkey="t"
            aria-label="Quickly jump between files">
        <span class="octicon octicon-list-unordered"></span>
      </a>
      <button aria-label="Copy file path to clipboard" class="js-zeroclipboard btn btn-sm zeroclipboard-button tooltipped tooltipped-s" data-copied-hint="Copied!" type="button"><span class="octicon octicon-clippy"></span></button>
    </div>

    <div class="breadcrumb js-zeroclipboard-target">
      <span class="repo-root js-repo-root"><span itemscope="" itemtype="http://data-vocabulary.org/Breadcrumb"><a href="/Xiaodan/RepData_PeerAssessment1" class="" data-branch="master" data-pjax="true" itemscope="url"><span itemprop="title">RepData_PeerAssessment1</span></a></span></span><span class="separator">/</span><strong class="final-path">PA1_template.md</strong>
    </div>
  </div>


  <div class="commit file-history-tease">
    <div class="file-history-tease-header">
        <img alt="@Xiaodan" class="avatar" height="24" src="https://avatars1.githubusercontent.com/u/1871047?v=3&amp;s=48" width="24" />
        <span class="author"><a href="/Xiaodan" rel="author">Xiaodan</a></span>
        <time datetime="2014-07-19T07:22:26Z" is="relative-time">Jul 19, 2014</time>
        <div class="commit-title">
            <a href="/Xiaodan/RepData_PeerAssessment1/commit/5aa8ccf61c4c25b826f22068b88dac63133e8984" class="message" data-pjax="true" title="Fixed bugs.">Fixed bugs.</a>
        </div>
    </div>

    <div class="participation">
      <p class="quickstat">
        <a href="#blob_contributors_box" rel="facebox">
          <strong>1</strong>
           contributor
        </a>
      </p>
      
    </div>
    <div id="blob_contributors_box" style="display:none">
      <h2 class="facebox-header">Users who have contributed to this file</h2>
      <ul class="facebox-user-list">
          <li class="facebox-user-list-item">
            <img alt="@Xiaodan" height="24" src="https://avatars1.githubusercontent.com/u/1871047?v=3&amp;s=48" width="24" />
            <a href="/Xiaodan">Xiaodan</a>
          </li>
      </ul>
    </div>
  </div>

<div class="file">
  <div class="file-header">
    <div class="file-actions">

      <div class="btn-group">
        <a href="/Xiaodan/RepData_PeerAssessment1/raw/master/PA1_template.md" class="btn btn-sm " id="raw-url">Raw</a>
          <a href="/Xiaodan/RepData_PeerAssessment1/blame/master/PA1_template.md" class="btn btn-sm js-update-url-with-hash">Blame</a>
        <a href="/Xiaodan/RepData_PeerAssessment1/commits/master/PA1_template.md" class="btn btn-sm " rel="nofollow">History</a>
      </div>

        <a class="octicon-btn tooltipped tooltipped-nw"
           href="github-windows://openRepo/https://github.com/Xiaodan/RepData_PeerAssessment1?branch=master&amp;filepath=PA1_template.md"
           aria-label="Open this file in GitHub Desktop"
           data-ga-click="Repository, open with desktop, type:windows">
            <span class="octicon octicon-desktop-download"></span>
        </a>

            <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="/Xiaodan/RepData_PeerAssessment1/edit/master/PA1_template.md" class="inline-form" data-form-nonce="4decf78111106bf20c7da0ccb4a1283e2db706cf" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="VZSwiVY58VLQoGcq09XJ8OU4hrHB5gbfM6VsstxZy3TzuSO2+CBehdf++le/AOtb2Mgdy6ozPEH3XFoSBBzG1Q==" /></div>
              <button class="octicon-btn tooltipped tooltipped-n" type="submit" aria-label="Edit the file in your fork of this project" data-hotkey="e" data-disable-with>
                <span class="octicon octicon-pencil"></span>
              </button>
</form>
          <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="/Xiaodan/RepData_PeerAssessment1/delete/master/PA1_template.md" class="inline-form" data-form-nonce="4decf78111106bf20c7da0ccb4a1283e2db706cf" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="g5AMMCyTNSAj5NI3+8PMeMZlxFdldzTNJNgXYK4wR+vNIp7bPKY+kmvTxorDR2/R06akex2mlTdZjTKpNwyjHA==" /></div>
            <button class="octicon-btn octicon-btn-danger tooltipped tooltipped-n" type="submit" aria-label="Delete this file in your fork of this project" data-disable-with>
              <span class="octicon octicon-trashcan"></span>
            </button>
</form>    </div>

    <div class="file-info">
        276 lines (206 sloc)
        <span class="file-info-divider"></span>
      7.193 kB
    </div>
  </div>
  
  <div id="readme" class="blob instapaper_body">
    <article class="markdown-body entry-content" itemprop="mainContentOfPage"><h1><a id="user-content-reproducible-research-peer-assessment-1" class="anchor" href="#reproducible-research-peer-assessment-1" aria-hidden="true"><span class="octicon octicon-link"></span></a>Reproducible Research: Peer Assessment 1</h1>

<h1></h1>

<p>Created by Xiaodan Zhang on July 18, 2014</p>

<h3><a id="user-content-basic-settings" class="anchor" href="#basic-settings" aria-hidden="true"><span class="octicon octicon-link"></span></a>Basic settings</h3>

<div class="highlight highlight-r"><pre><span class="pl-v">echo</span> <span class="pl-k">=</span> <span class="pl-c1">TRUE</span>  <span class="pl-c"># Always make code visible</span>
options(<span class="pl-v">scipen</span> <span class="pl-k">=</span> <span class="pl-c1">1</span>)  <span class="pl-c"># Turn off scientific notations for numbers</span></pre></div>

<h3><a id="user-content-loading-and-processing-the-data" class="anchor" href="#loading-and-processing-the-data" aria-hidden="true"><span class="octicon octicon-link"></span></a>Loading and processing the data</h3>

<div class="highlight highlight-r"><pre>unzip(<span class="pl-s"><span class="pl-pds">"</span>activity.zip<span class="pl-pds">"</span></span>)
<span class="pl-smi">data</span> <span class="pl-k">&lt;-</span> read.csv(<span class="pl-s"><span class="pl-pds">"</span>activity.csv<span class="pl-pds">"</span></span>, <span class="pl-v">colClasses</span> <span class="pl-k">=</span> c(<span class="pl-s"><span class="pl-pds">"</span>integer<span class="pl-pds">"</span></span>, <span class="pl-s"><span class="pl-pds">"</span>Date<span class="pl-pds">"</span></span>, <span class="pl-s"><span class="pl-pds">"</span>factor<span class="pl-pds">"</span></span>))
<span class="pl-smi">data</span><span class="pl-k">$</span><span class="pl-smi">month</span> <span class="pl-k">&lt;-</span> as.numeric(format(<span class="pl-smi">data</span><span class="pl-k">$</span><span class="pl-smi">date</span>, <span class="pl-s"><span class="pl-pds">"</span>%m<span class="pl-pds">"</span></span>))
<span class="pl-smi">noNA</span> <span class="pl-k">&lt;-</span> na.omit(<span class="pl-smi">data</span>)
rownames(<span class="pl-smi">noNA</span>) <span class="pl-k">&lt;-</span> <span class="pl-c1">1</span><span class="pl-k">:</span>nrow(<span class="pl-smi">noNA</span>)
head(<span class="pl-smi">noNA</span>)</pre></div>

<pre><code>##   steps       date interval month
## 1     0 2012-10-02        0    10
## 2     0 2012-10-02        5    10
## 3     0 2012-10-02       10    10
## 4     0 2012-10-02       15    10
## 5     0 2012-10-02       20    10
## 6     0 2012-10-02       25    10
</code></pre>

<div class="highlight highlight-r"><pre>dim(<span class="pl-smi">noNA</span>)</pre></div>

<pre><code>## [1] 15264     4
</code></pre>

<div class="highlight highlight-r"><pre>library(<span class="pl-smi">ggplot2</span>)</pre></div>

<h3><a id="user-content-what-is-mean-total-number-of-steps-taken-per-day" class="anchor" href="#what-is-mean-total-number-of-steps-taken-per-day" aria-hidden="true"><span class="octicon octicon-link"></span></a>What is mean total number of steps taken per day?</h3>

<p>For this part of the assignment, you can ignore the missing values in the dataset.</p>

<ul>
<li>Make a histogram of the total number of steps taken each day</li>
</ul>

<div class="highlight highlight-r"><pre>ggplot(<span class="pl-smi">noNA</span>, aes(<span class="pl-smi">date</span>, <span class="pl-smi">steps</span>)) <span class="pl-k">+</span> geom_bar(<span class="pl-v">stat</span> <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">"</span>identity<span class="pl-pds">"</span></span>, <span class="pl-v">colour</span> <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">"</span>steelblue<span class="pl-pds">"</span></span>, <span class="pl-v">fill</span> <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">"</span>steelblue<span class="pl-pds">"</span></span>, <span class="pl-v">width</span> <span class="pl-k">=</span> <span class="pl-c1">0.7</span>) <span class="pl-k">+</span> facet_grid(. <span class="pl-k">~</span> <span class="pl-smi">month</span>, <span class="pl-v">scales</span> <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">"</span>free<span class="pl-pds">"</span></span>) <span class="pl-k">+</span> labs(<span class="pl-v">title</span> <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">"</span>Histogram of Total Number of Steps Taken Each Day<span class="pl-pds">"</span></span>, <span class="pl-v">x</span> <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">"</span>Date<span class="pl-pds">"</span></span>, <span class="pl-v">y</span> <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">"</span>Total number of steps<span class="pl-pds">"</span></span>)</pre></div>

<p><a href="/Xiaodan/RepData_PeerAssessment1/blob/master/figure/unnamed-chunk-3.png" target="_blank"><img src="/Xiaodan/RepData_PeerAssessment1/raw/master/figure/unnamed-chunk-3.png" alt="plot of chunk unnamed-chunk-3" style="max-width:100%;"></a> </p>

<ul>
<li>Calculate and report the mean and median total number of steps taken per day</li>
</ul>

<p>Mean total number of steps taken per day:</p>

<div class="highlight highlight-r"><pre><span class="pl-smi">totalSteps</span> <span class="pl-k">&lt;-</span> aggregate(<span class="pl-smi">noNA</span><span class="pl-k">$</span><span class="pl-smi">steps</span>, <span class="pl-k">list</span>(<span class="pl-v">Date</span> <span class="pl-k">=</span> <span class="pl-smi">noNA</span><span class="pl-k">$</span><span class="pl-smi">date</span>), <span class="pl-v">FUN</span> <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">"</span>sum<span class="pl-pds">"</span></span>)<span class="pl-k">$</span><span class="pl-smi">x</span>
mean(<span class="pl-smi">totalSteps</span>)</pre></div>

<pre><code>## [1] 10766
</code></pre>

<p>Median total number of steps taken per day:</p>

<div class="highlight highlight-r"><pre>median(<span class="pl-smi">totalSteps</span>)</pre></div>

<pre><code>## [1] 10765
</code></pre>

<h3><a id="user-content-what-is-the-average-daily-activity-pattern" class="anchor" href="#what-is-the-average-daily-activity-pattern" aria-hidden="true"><span class="octicon octicon-link"></span></a>What is the average daily activity pattern?</h3>

<ul>
<li>Make a time series plot (i.e. type = "l") of the 5-minute interval (x-axis) and the average number of steps taken, averaged across all days (y-axis)</li>
</ul>

<div class="highlight highlight-r"><pre><span class="pl-smi">avgSteps</span> <span class="pl-k">&lt;-</span> aggregate(<span class="pl-smi">noNA</span><span class="pl-k">$</span><span class="pl-smi">steps</span>, <span class="pl-k">list</span>(<span class="pl-v">interval</span> <span class="pl-k">=</span> as.numeric(as.character(<span class="pl-smi">noNA</span><span class="pl-k">$</span><span class="pl-smi">interval</span>))), <span class="pl-v">FUN</span> <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">"</span>mean<span class="pl-pds">"</span></span>)
names(<span class="pl-smi">avgSteps</span>)[<span class="pl-c1">2</span>] <span class="pl-k">&lt;-</span> <span class="pl-s"><span class="pl-pds">"</span>meanOfSteps<span class="pl-pds">"</span></span>

ggplot(<span class="pl-smi">avgSteps</span>, aes(<span class="pl-smi">interval</span>, <span class="pl-smi">meanOfSteps</span>)) <span class="pl-k">+</span> geom_line(<span class="pl-v">color</span> <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">"</span>steelblue<span class="pl-pds">"</span></span>, <span class="pl-v">size</span> <span class="pl-k">=</span> <span class="pl-c1">0.8</span>) <span class="pl-k">+</span> labs(<span class="pl-v">title</span> <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">"</span>Time Series Plot of the 5-minute Interval<span class="pl-pds">"</span></span>, <span class="pl-v">x</span> <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">"</span>5-minute intervals<span class="pl-pds">"</span></span>, <span class="pl-v">y</span> <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">"</span>Average Number of Steps Taken<span class="pl-pds">"</span></span>)</pre></div>

<p><a href="/Xiaodan/RepData_PeerAssessment1/blob/master/figure/unnamed-chunk-6.png" target="_blank"><img src="/Xiaodan/RepData_PeerAssessment1/raw/master/figure/unnamed-chunk-6.png" alt="plot of chunk unnamed-chunk-6" style="max-width:100%;"></a> </p>

<ul>
<li>Which 5-minute interval, on average across all the days in the dataset, contains the maximum number of steps?</li>
</ul>

<div class="highlight highlight-r"><pre><span class="pl-smi">avgSteps</span>[<span class="pl-smi">avgSteps</span><span class="pl-k">$</span><span class="pl-smi">meanOfSteps</span> <span class="pl-k">==</span> max(<span class="pl-smi">avgSteps</span><span class="pl-k">$</span><span class="pl-smi">meanOfSteps</span>), ]</pre></div>

<pre><code>##     interval meanOfSteps
## 104      835       206.2
</code></pre>

<h3><a id="user-content-imputing-missing-values" class="anchor" href="#imputing-missing-values" aria-hidden="true"><span class="octicon octicon-link"></span></a>Imputing missing values</h3>

<ul>
<li>The total number of rows with NAs:</li>
</ul>

<div class="highlight highlight-r"><pre>sum(is.na(<span class="pl-smi">data</span>))</pre></div>

<pre><code>## [1] 2304
</code></pre>

<ul>
<li>Devise a strategy for filling in all of the missing values in the dataset. The strategy does not need to be sophisticated. For example, you could use the mean/median for that day, or the mean for that 5-minute interval, etc.</li>
</ul>

<p>My strategy is to use the mean for that 5-minute interval to fill each NA value in the steps column.</p>

<ul>
<li>Create a new dataset that is equal to the original dataset but with the missing data filled in.</li>
</ul>

<div class="highlight highlight-r"><pre><span class="pl-smi">newData</span> <span class="pl-k">&lt;-</span> <span class="pl-smi">data</span> 
<span class="pl-k">for</span> (<span class="pl-smi">i</span> <span class="pl-k">in</span> <span class="pl-c1">1</span><span class="pl-k">:</span>nrow(<span class="pl-smi">newData</span>)) {
    <span class="pl-k">if</span> (is.na(<span class="pl-smi">newData</span><span class="pl-k">$</span><span class="pl-smi">steps</span>[<span class="pl-smi">i</span>])) {
        <span class="pl-smi">newData</span><span class="pl-k">$</span><span class="pl-smi">steps</span>[<span class="pl-smi">i</span>] <span class="pl-k">&lt;-</span> <span class="pl-smi">avgSteps</span>[which(<span class="pl-smi">newData</span><span class="pl-k">$</span><span class="pl-smi">interval</span>[<span class="pl-smi">i</span>] <span class="pl-k">==</span> <span class="pl-smi">avgSteps</span><span class="pl-k">$</span><span class="pl-smi">interval</span>), ]<span class="pl-k">$</span><span class="pl-smi">meanOfSteps</span>
    }
}

head(<span class="pl-smi">newData</span>)</pre></div>

<pre><code>##     steps       date interval month
## 1 1.71698 2012-10-01        0    10
## 2 0.33962 2012-10-01        5    10
## 3 0.13208 2012-10-01       10    10
## 4 0.15094 2012-10-01       15    10
## 5 0.07547 2012-10-01       20    10
## 6 2.09434 2012-10-01       25    10
</code></pre>

<div class="highlight highlight-r"><pre>sum(is.na(<span class="pl-smi">newData</span>))</pre></div>

<pre><code>## [1] 0
</code></pre>

<ul>
<li>Make a histogram of the total number of steps taken each day and Calculate and report the mean and median total number of steps taken per day. </li>
</ul>

<div class="highlight highlight-r"><pre>ggplot(<span class="pl-smi">newData</span>, aes(<span class="pl-smi">date</span>, <span class="pl-smi">steps</span>)) <span class="pl-k">+</span> geom_bar(<span class="pl-v">stat</span> <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">"</span>identity<span class="pl-pds">"</span></span>,
                                             <span class="pl-v">colour</span> <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">"</span>steelblue<span class="pl-pds">"</span></span>,
                                             <span class="pl-v">fill</span> <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">"</span>steelblue<span class="pl-pds">"</span></span>,
                                             <span class="pl-v">width</span> <span class="pl-k">=</span> <span class="pl-c1">0.7</span>) <span class="pl-k">+</span> facet_grid(. <span class="pl-k">~</span> <span class="pl-smi">month</span>, <span class="pl-v">scales</span> <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">"</span>free<span class="pl-pds">"</span></span>) <span class="pl-k">+</span> labs(<span class="pl-v">title</span> <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">"</span>Histogram of Total Number of Steps Taken Each Day (no missing data)<span class="pl-pds">"</span></span>, <span class="pl-v">x</span> <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">"</span>Date<span class="pl-pds">"</span></span>, <span class="pl-v">y</span> <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">"</span>Total number of steps<span class="pl-pds">"</span></span>)</pre></div>

<p><a href="/Xiaodan/RepData_PeerAssessment1/blob/master/figure/unnamed-chunk-10.png" target="_blank"><img src="/Xiaodan/RepData_PeerAssessment1/raw/master/figure/unnamed-chunk-10.png" alt="plot of chunk unnamed-chunk-10" style="max-width:100%;"></a> </p>

<ul>
<li>Do these values differ from the estimates from the first part of the assignment? What is the impact of imputing missing data on the estimates of the total daily number of steps?</li>
</ul>

<p>Mean total number of steps taken per day:</p>

<div class="highlight highlight-r"><pre><span class="pl-smi">newTotalSteps</span> <span class="pl-k">&lt;-</span> aggregate(<span class="pl-smi">newData</span><span class="pl-k">$</span><span class="pl-smi">steps</span>, 
                           <span class="pl-k">list</span>(<span class="pl-v">Date</span> <span class="pl-k">=</span> <span class="pl-smi">newData</span><span class="pl-k">$</span><span class="pl-smi">date</span>), 
                           <span class="pl-v">FUN</span> <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">"</span>sum<span class="pl-pds">"</span></span>)<span class="pl-k">$</span><span class="pl-smi">x</span>
<span class="pl-smi">newMean</span> <span class="pl-k">&lt;-</span> mean(<span class="pl-smi">newTotalSteps</span>)
<span class="pl-smi">newMean</span></pre></div>

<pre><code>## [1] 10766
</code></pre>

<p>Median total number of steps taken per day:</p>

<div class="highlight highlight-r"><pre><span class="pl-smi">newMedian</span> <span class="pl-k">&lt;-</span> median(<span class="pl-smi">newTotalSteps</span>)
<span class="pl-smi">newMedian</span></pre></div>

<pre><code>## [1] 10766
</code></pre>

<p>Compare them with the two before imputing missing data:</p>

<div class="highlight highlight-r"><pre><span class="pl-smi">oldMean</span> <span class="pl-k">&lt;-</span> mean(<span class="pl-smi">totalSteps</span>)
<span class="pl-smi">oldMedian</span> <span class="pl-k">&lt;-</span> median(<span class="pl-smi">totalSteps</span>)
<span class="pl-smi">newMean</span> <span class="pl-k">-</span> <span class="pl-smi">oldMean</span></pre></div>

<pre><code>## [1] 0
</code></pre>

<div class="highlight highlight-r"><pre><span class="pl-smi">newMedian</span> <span class="pl-k">-</span> <span class="pl-smi">oldMedian</span></pre></div>

<pre><code>## [1] 1.189
</code></pre>

<p>So, after imputing the missing data, the new mean of total steps taken per day is the same as that of the old mean; the new median of total steps taken per day is greater than that of the old median.</p>

<h3><a id="user-content-are-there-differences-in-activity-patterns-between-weekdays-and-weekends" class="anchor" href="#are-there-differences-in-activity-patterns-between-weekdays-and-weekends" aria-hidden="true"><span class="octicon octicon-link"></span></a>Are there differences in activity patterns between weekdays and weekends?</h3>

<ul>
<li>Create a new factor variable in the dataset with two levels -- "weekday" and "weekend" indicating whether a given date is a weekday or weekend day.</li>
</ul>

<div class="highlight highlight-r"><pre>head(<span class="pl-smi">newData</span>)</pre></div>

<pre><code>##     steps       date interval month
## 1 1.71698 2012-10-01        0    10
## 2 0.33962 2012-10-01        5    10
## 3 0.13208 2012-10-01       10    10
## 4 0.15094 2012-10-01       15    10
## 5 0.07547 2012-10-01       20    10
## 6 2.09434 2012-10-01       25    10
</code></pre>

<div class="highlight highlight-r"><pre><span class="pl-smi">newData</span><span class="pl-k">$</span><span class="pl-smi">weekdays</span> <span class="pl-k">&lt;-</span> <span class="pl-k">factor</span>(format(<span class="pl-smi">newData</span><span class="pl-k">$</span><span class="pl-smi">date</span>, <span class="pl-s"><span class="pl-pds">"</span>%A<span class="pl-pds">"</span></span>))
levels(<span class="pl-smi">newData</span><span class="pl-k">$</span><span class="pl-smi">weekdays</span>)</pre></div>

<pre><code>## [1] "Friday"    "Monday"    "Saturday"  "Sunday"    "Thursday"  "Tuesday"  
## [7] "Wednesday"
</code></pre>

<div class="highlight highlight-r"><pre>levels(<span class="pl-smi">newData</span><span class="pl-k">$</span><span class="pl-smi">weekdays</span>) <span class="pl-k">&lt;-</span> <span class="pl-k">list</span>(<span class="pl-v">weekday</span> <span class="pl-k">=</span> c(<span class="pl-s"><span class="pl-pds">"</span>Monday<span class="pl-pds">"</span></span>, <span class="pl-s"><span class="pl-pds">"</span>Tuesday<span class="pl-pds">"</span></span>,
                                             <span class="pl-s"><span class="pl-pds">"</span>Wednesday<span class="pl-pds">"</span></span>, 
                                             <span class="pl-s"><span class="pl-pds">"</span>Thursday<span class="pl-pds">"</span></span>, <span class="pl-s"><span class="pl-pds">"</span>Friday<span class="pl-pds">"</span></span>),
                                 <span class="pl-v">weekend</span> <span class="pl-k">=</span> c(<span class="pl-s"><span class="pl-pds">"</span>Saturday<span class="pl-pds">"</span></span>, <span class="pl-s"><span class="pl-pds">"</span>Sunday<span class="pl-pds">"</span></span>))
levels(<span class="pl-smi">newData</span><span class="pl-k">$</span><span class="pl-smi">weekdays</span>)</pre></div>

<pre><code>## [1] "weekday" "weekend"
</code></pre>

<div class="highlight highlight-r"><pre>table(<span class="pl-smi">newData</span><span class="pl-k">$</span><span class="pl-smi">weekdays</span>)</pre></div>

<pre><code>## 
## weekday weekend 
##   12960    4608
</code></pre>

<ul>
<li>Make a panel plot containing a time series plot (i.e. type = "l") of the 5-minute interval (x-axis) and the average number of steps taken, averaged across all weekday days or weekend days (y-axis).</li>
</ul>

<div class="highlight highlight-r"><pre><span class="pl-smi">avgSteps</span> <span class="pl-k">&lt;-</span> aggregate(<span class="pl-smi">newData</span><span class="pl-k">$</span><span class="pl-smi">steps</span>, 
                      <span class="pl-k">list</span>(<span class="pl-v">interval</span> <span class="pl-k">=</span> as.numeric(as.character(<span class="pl-smi">newData</span><span class="pl-k">$</span><span class="pl-smi">interval</span>)), 
                           <span class="pl-v">weekdays</span> <span class="pl-k">=</span> <span class="pl-smi">newData</span><span class="pl-k">$</span><span class="pl-smi">weekdays</span>),
                      <span class="pl-v">FUN</span> <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">"</span>mean<span class="pl-pds">"</span></span>)
names(<span class="pl-smi">avgSteps</span>)[<span class="pl-c1">3</span>] <span class="pl-k">&lt;-</span> <span class="pl-s"><span class="pl-pds">"</span>meanOfSteps<span class="pl-pds">"</span></span>
library(<span class="pl-smi">lattice</span>)
xyplot(<span class="pl-smi">avgSteps</span><span class="pl-k">$</span><span class="pl-smi">meanOfSteps</span> <span class="pl-k">~</span> <span class="pl-smi">avgSteps</span><span class="pl-k">$</span><span class="pl-smi">interval</span> <span class="pl-k">|</span> <span class="pl-smi">avgSteps</span><span class="pl-k">$</span><span class="pl-smi">weekdays</span>, 
       <span class="pl-v">layout</span> <span class="pl-k">=</span> c(<span class="pl-c1">1</span>, <span class="pl-c1">2</span>), <span class="pl-v">type</span> <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">"</span>l<span class="pl-pds">"</span></span>, 
       <span class="pl-v">xlab</span> <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">"</span>Interval<span class="pl-pds">"</span></span>, <span class="pl-v">ylab</span> <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">"</span>Number of steps<span class="pl-pds">"</span></span>)</pre></div>

<p><a href="/Xiaodan/RepData_PeerAssessment1/blob/master/figure/unnamed-chunk-15.png" target="_blank"><img src="/Xiaodan/RepData_PeerAssessment1/raw/master/figure/unnamed-chunk-15.png" alt="plot of chunk unnamed-chunk-15" style="max-width:100%;"></a> </p>
</article>
  </div>

</div>

<a href="#jump-to-line" rel="facebox[.linejump]" data-hotkey="l" style="display:none">Jump to Line</a>
<div id="jump-to-line" style="display:none">
  <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="" class="js-jump-to-line-form" method="get"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /></div>
    <input class="linejump-input js-jump-to-line-field" type="text" placeholder="Jump to line&hellip;" aria-label="Jump to line" autofocus>
    <button type="submit" class="btn">Go</button>
</form></div>

          </div>
        </div>
        <div class="modal-backdrop"></div>
      </div>
  </div>


    </div><!-- /.wrapper -->

      <div class="container">
  <div class="site-footer" role="contentinfo">
    <ul class="site-footer-links right">
        <li><a href="https://status.github.com/" data-ga-click="Footer, go to status, text:status">Status</a></li>
      <li><a href="https://developer.github.com" data-ga-click="Footer, go to api, text:api">API</a></li>
      <li><a href="https://training.github.com" data-ga-click="Footer, go to training, text:training">Training</a></li>
      <li><a href="https://shop.github.com" data-ga-click="Footer, go to shop, text:shop">Shop</a></li>
        <li><a href="https://github.com/blog" data-ga-click="Footer, go to blog, text:blog">Blog</a></li>
        <li><a href="https://github.com/about" data-ga-click="Footer, go to about, text:about">About</a></li>
        <li><a href="https://help.github.com" data-ga-click="Footer, go to help, text:help">Help</a></li>

    </ul>

    <a href="https://github.com" aria-label="Homepage">
      <span class="mega-octicon octicon-mark-github" title="GitHub"></span>
</a>
    <ul class="site-footer-links">
      <li>&copy; 2015 <span title="0.05673s from github-fe134-cp1-prd.iad.github.net">GitHub</span>, Inc.</li>
        <li><a href="https://github.com/site/terms" data-ga-click="Footer, go to terms, text:terms">Terms</a></li>
        <li><a href="https://github.com/site/privacy" data-ga-click="Footer, go to privacy, text:privacy">Privacy</a></li>
        <li><a href="https://github.com/security" data-ga-click="Footer, go to security, text:security">Security</a></li>
        <li><a href="https://github.com/contact" data-ga-click="Footer, go to contact, text:contact">Contact</a></li>
    </ul>
  </div>
</div>


    <div class="fullscreen-overlay js-fullscreen-overlay" id="fullscreen_overlay">
  <div class="fullscreen-container js-suggester-container">
    <div class="textarea-wrap">
      <textarea name="fullscreen-contents" id="fullscreen-contents" class="fullscreen-contents js-fullscreen-contents" placeholder="" aria-label=""></textarea>
      <div class="suggester-container">
        <div class="suggester fullscreen-suggester js-suggester js-navigation-container"></div>
      </div>
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
      <a href="#" class="octicon octicon-x flash-close js-ajax-error-dismiss" aria-label="Dismiss error"></a>
      Something went wrong with that request. Please try again.
    </div>


      <script crossorigin="anonymous" src="https://assets-cdn.github.com/assets/frameworks-55bdb89972afd4b256fc7c3ed42001976a03fb3eaba96e625d5806c659bc19c6.js"></script>
      <script async="async" crossorigin="anonymous" src="https://assets-cdn.github.com/assets/github/index-fe2e1fa6704baa94c97c39847254262f674803845a2b1addd89d4f9eca3fa297.js"></script>
      
      
    <div class="js-stale-session-flash stale-session-flash flash flash-warn flash-banner hidden">
      <span class="octicon octicon-alert"></span>
      <span class="signed-in-tab-flash">You signed in with another tab or window. <a href="">Reload</a> to refresh your session.</span>
      <span class="signed-out-tab-flash">You signed out in another tab or window. <a href="">Reload</a> to refresh your session.</span>
    </div>
  </body>
</html>

