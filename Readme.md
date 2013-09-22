## Varnish:

  - [Global Varnish Cluster with GeoDNS](http://www.slideshare.net/kimlindholm/globalvarnish-cluster-with-geodns)

  - [How to build your own CDN using BIND, GeoIP, Nginx, and Varnish, 2010.07](http://blog.unixy.net/2010/07/how-to-build-your-own-cdn-using-bind-geoip-nginx-and-varnish/)

  - [Ultra-Performant Dynamic Websites with Varnish - Lidl.de, 2012.01](http://blog.mgm-tp.com/2012/01/varnish-web-cache/)
  - [Realtime stats from Varnish, 2013.02](http://jiboumans.wordpress.com/2013/02/27/realtime-stats-from-varnish/)
  - [Context-aware HTTP caching, 2012.09](http://asm89.github.io/2012/09/26/context-aware-http-caching.html)
  - [Simple scales faster and better in the real world - Video](http://vimeo.com/album/2525252/video/74388108)
  - [Setup Varnish as an API Proxy](https://support.3scale.net/howtos/api-configuration/varnish)
  - [Varnish in Five Acts, 2013.05](http://dev.theladders.com/2013/05/varnish-in-five-acts/)
  - [Packaging Varnish VMODs, 2013.06](http://www.kreuzwerker.de/en/blog/packaging-varnish-vmods/)

## Invalidation/Purging
  - [Tagged Cache Invalidation, 2012.09](http://blog.kevburnsjr.com/tagged-cache-invalidation)
  - [Varnish in Five Acts, 2013.05](http://dev.theladders.com/2013/05/varnish-in-five-acts/)


## Slides
  - [Varnish @ Angrybirds - Overview for a High Performance Shop, 2013.09](http://www.slideshare.net/aoepeople/angrybirds-overview-for-a-high-performance-shop-stockholm)
  - [Caching is Hard: Varnish @ Disqus, 2013.05](https://speakerdeck.com/mattrobenolt/caching-is-hard-varnish-at-disqus)
  - [Lost in Translation:varnishlog, varnishtest(VUG7), 2013.05](http://www.slideshare.net/xcir/varnish-user-group-meeting-7final-ver)
  - [How Varnish & MongoDB Scale Business Insider, 2013.05](http://www.slideshare.net/paxdickinson/scaling-business-insider)
  - [Varnish at the BBC, 2012.10](http://www.slideshare.net/grahamlyons/varnish-at-the-bbc)
  - [Varnish @ VGnet](http://www.vg.no/presentations/slides/VUG2012.html)
  - [Varnish @ Holiday-extras.com](https://www.varnish-cache.org/sites/default/files/10_Varnish_Presentation_Holidays-Extras.pdf)
  - [Varnish @ Opera](http://www.slideshare.net/cstrep/vug5-varnish-at-opera-software/)
  - [dClass and Varnish](http://www.slideshare.net/rezanaghibi/dclass)
  - [Wetter.com case study, 2012.06](https://speakerdeck.com/gaylord/wettercom-case-study-on-symfony_live-2012-paris)
  - [Loadbalancing 101](https://speakerdeck.com/bradwhittington/load-balancing-101)
  - [Varnish @ Lanyrd, 2013.03](https://speakerdeck.com/andrewgodwin/inside-lanyrds-architecture)
  - [Varnish @ Kiveda, 2013.05](https://speakerdeck.com/dzuelke/surviving-a-prime-time-tv-commercial-sfliveportland2013-2013-05-23)



## Examples for VCL
  - https://github.com/metabrainz/3scale-vcl.git
  - https://github.com/mattiasgeniar/varnish-3.0-configuration-templates.git

## HowTo Modules
  - [Testing VMODs with Travis.CI, 2013.09](http://lassekarstensen.wordpress.com/2013/09/10/testing-vmods-with-travis-travis-ci-org/)
  - [The essential vmods all Varnish users should know about, 2013.07](https://www.varnish-software.com/blog/essential-vmods-all-varnish-users-should-know-about)
  - [Building a Varnish VMOD on Debian, 2013.07](http://lassekarstensen.wordpress.com/2013/07/29/building-a-varnish-vmod-on-debian/)

## [Modules](https://www.varnish-cache.org/vmods)
  - [Varnish: Reject or delay requests after given tresholds are reached. (Think API rate limit, or per-ip MISS rate limit)](https://github.com/nand2/libvmod-throttle.git)
  - [A fast Varnish module for sorting query string parameters.](https://github.com/vimeo/libvmod-boltsort.git)
  - [LDAP module for Varnish](https://github.com/xcir/libvmod-ldap.git)
  - [Varnish vmod DNS functions](https://github.com/kenshaw/libvmod-dns.git)
  - [X-Vary-Options for Varnish](https://github.com/atdt/xvo.git)
  - [Access to various timers in Varnish](https://github.com/jib/libvmod-timers.git)
  - [Varnish module to send statistics to statsd](https://github.com/jib/libvmod-statsd.git)
  - [A Varnish module that allows sending commands to redis from the VCL](https://github.com/csfrancis/libvmod-redis.git)
  - [A varnish vmod for simpler use of the cookie header](https://github.com/lkarsten/libvmod-cookie.git)
  - [Varnish lua vmod to execute lua script in VCL](https://github.com/flygoast/libvmod-lua.git)
  - [VMOD for Varnish Cache which adds time utilities](https://github.com/jthomerson/libvmod-timeutils.git)
  - [Varnish VMOD to send data over UDP from VCL](https://github.com/mmb/vmod_dgram.git)
  - [cURL bindings for Varnish through the Varnish Module interface](https://github.com/varnish/libvmod-curl.git)
  - [Variable support VMOD](https://github.com/varnish/libvmod-var.git)
  - [A general-purpose querystring manipulation module for Varnish](https://github.com/Dridi/libvmod-querystring.git)
  - [Dynamic backend](https://github.com/xcir/libvmod-backendutils.git)
  - [parsing post,get,cookie data](https://github.com/xcir/libvmod-parsereq.git)
  - [dClass - Pattern Classification Engine](https://github.com/TheWeatherChannel/dClass.git)
  - [API Proxy](https://github.com/3scale/libvmod-3scale.git), [Official](https://www.varnish-cache.org/vmod/api-proxy)
  - [Varnish Shield Module - Provides basic means for DDoS protection](https://github.com/varnish/libvmod-shield.git)
  - [Setting client.ip in Varnish VCL with libvmod-ipcast](https://github.com/lkarsten/libvmod-ipcast.git)

## Misc
  - [Test framework written in Ruby to test varnish-cache routing and caching logic](https://github.com/TV4/Urushiol.git)
  - [Varnish Bans Manager (VBM) is a simple server and web UI designed to ease management of bans in complex Varnish deployments](https://github.com/dot2code/varnish-bans-manager)
  - [Varnish Security Firewall](https://github.com/comotion/VSF.git)
  - [Re-format tool for vsl(varnishlog)](https://github.com/xcir/vsltrans.git)



## User Groups
  - https://www.varnish-cache.org/vug7/
  - https://www.varnish-cache.org/vug6/
  - https://www.varnish-cache.org/vug5/
  - https://www.varnish-cache.org/vug4/

## Books
  - [Varnish System Administration](https://www.varnish-software.com/static/pdfs/varnish-book-4.2-dirty.pdf)

## Balancer in general
  - https://github.com/observing/balancerbattle

## Fastly
  - https://github.com/fastly

<!-- PROJECTS_LIST_START -->
    *** GENERATED BY https://github.com/mindreframer/techwatcher (ruby _sh/pull varnish-stuff) *** 

    3scale/libvmod-3scale:
      An example vmod for Varnish
       82 commits, last change: 2013-06-28 02:00:40, 13 stars, 40 forks

    allancrooks/vcl-cache-validation:
      VCL scripts for Varnish Cache to enforce cache content validation
       11 commits, last change: 2013-04-16 12:27:01, 0 stars, 0 forks

    andreacampi/varnish-rb:
      varnish-rb provides a bridge between Ruby and Varnish 3
       32 commits, last change: 2013-03-29 14:54:19, 8 stars, 3 forks

    atdt/xvo:
      X-Vary-Options for Varnish
       4 commits, last change: 2013-08-23 11:24:26, 1 stars, 0 forks

    camptocamp/puppet-varnish:

       83 commits, last change: 2013-09-10 06:23:03, 39 stars, 25 forks

    comotion/VSF:
      Varnish Security Firewall
       10 commits, last change: 2012-10-23 06:50:52, 19 stars, 7 forks

    csfrancis/libvmod-redis:
      An example vmod for Varnish
       39 commits, last change: 2013-07-16 06:28:20, 0 stars, 40 forks

    dot2code/varnish-bans-manager:
      Varnish Bans Manager (VBM) is a simple server and web UI designed to ease management of bans in complex Varnish deployments
       165 commits, last change: 2013-05-13 03:12:45, 13 stars, 1 forks

    dreamhost/varnish-vcl-collection:
      Collection of Varnish VCL files
       5 commits, last change: 2013-09-05 17:50:13, 5 stars, 0 forks

    Dridi/libvmod-querystring:
      A general-purpose querystring manipulation module for Varnish
       40 commits, last change: 2013-07-22 22:09:26, 13 stars, 5 forks

    flygoast/libvmod-lua:
      Varnish lua vmod to execute lua script in VCL.
       1 commits, last change: 2013-05-30 09:07:52, 3 stars, 0 forks

    Fotolia/varnishops:
      a CLI realtime varnish traffic analyzer
       18 commits, last change: 2013-05-28 01:30:26, 9 stars, 3 forks

    hellvinz/purger:
      client to purgerd. Send bans to varnish from ruby
       8 commits, last change: 2012-11-08 10:16:37, 1 stars, 0 forks

    hellvinz/purgerd:
      forward purge to a pool of varnish
       22 commits, last change: 2013-05-16 14:35:01, 2 stars, 0 forks

    inviqa/chef-varnish:
      Chef cookbook that configures the varnish-cache.org repos for apt or yum and installs and configures Varnish 3.* based on the defined attributes.
       25 commits, last change: 2012-10-17 08:03:42, 6 stars, 8 forks

    jcihocki/varnishd-skillshare:
      Accompanying test app with stepped branches for my varnishd skillshare class
       23 commits, last change: 2013-07-20 15:06:13, 0 stars, 0 forks

    jib/libvmod-statsd:
      Varnish module to send statistics to statsd
       36 commits, last change: 2013-09-05 16:38:00, 25 stars, 5 forks

    jib/libvmod-timers:
      Access to various timers in Varnish
       25 commits, last change: 2013-03-26 17:04:41, 8 stars, 2 forks

    jthomerson/libvmod-timeutils:
      VMOD for Varnish Cache which adds time utilities.
       5 commits, last change: 2012-10-22 08:03:16, 5 stars, 1 forks

    kenshaw/libvmod-dns:
      Varnish vmod DNS functions
       11 commits, last change: 2013-06-24 01:37:59, 3 stars, 0 forks

    lkarsten/libvmod-cookie:
      A varnish vmod for simpler use of the cookie header
       62 commits, last change: 2013-09-10 05:35:48, 14 stars, 2 forks

    lkarsten/libvmod-ipcast:
      libvmod-ipcast
       49 commits, last change: 2013-07-31 01:59:13, 6 stars, 1 forks

    luctus/chef-varnish-dashboard:
      A chef recipe for the amazing Varnish Agent Dashboard (A real time Varnish Cache metrics dashboard)
       6 commits, last change: 2013-06-19 06:18:04, 1 stars, 0 forks

    madepeople/Made_Cache:
      Advanced Block Cache module for Magento that supports Varnish + ESI
       38 commits, last change: 2013-08-28 08:46:34, 23 stars, 6 forks

    mattiasgeniar/varnish-3.0-configuration-templates:
      Configuration templates used for Varnish 3.0 implementations
       99 commits, last change: 2013-05-22 00:32:42, 149 stars, 31 forks

    metabrainz/3scale-vcl:
      A draft Varnish configuration to talk to 3scale
       1 commits, last change: 2012-03-13 11:22:27, 0 stars, 0 forks

    mmb/vmod_dgram:
      Varnish VMOD to send data over UDP from VCL.
       14 commits, last change: 2013-06-16 01:51:09, 3 stars, 0 forks

    nand2/libvmod-throttle:
      Varnish: Reject or delay requests after given tresholds are reached. (Think API rate limit, or per-ip MISS rate limit)
       59 commits, last change: 2013-08-26 04:55:50, 28 stars, 7 forks

    observing/balancerbattle:
      WebSocket loadbalancer battle
       53 commits, last change: 2013-05-24 01:27:01, 249 stars, 14 forks

    pad92/varnish:
      Varnish minimal configuration (use builtin for best performances)
       3 commits, last change: 2013-08-21 18:16:12, 0 stars, 0 forks

    pbruna/Varnish-Agent-Dashboard:
      Real time Varnish Cache metrics dashboard
       132 commits, last change: 2013-04-29 08:06:41, 108 stars, 9 forks

    robmiller/varnisher:
      A library and command-line tool, written in Ruby, for working with the Varnish HTTP cache
       105 commits, last change: 2013-09-12 04:01:06, 15 stars, 1 forks

    robszumski/varnish_etcd:
      Dynamically apply Varnish VCL based on data from etcd
       3 commits, last change: 2013-09-04 22:19:25, 0 stars, 0 forks

    samlbits/puppet-varnish:
      A varnish module for the samlbits.net CDN
       50 commits, last change: 2013-09-19 12:33:02, 0 stars, 0 forks

    TheWeatherChannel/dClass:
      Device Classification Engine
       131 commits, last change: 2013-08-07 07:46:48, 33 stars, 11 forks

    ThijsFeryn/varnishtraining:
      Vagrant box including VCL's  examples for my Varnish training
       14 commits, last change: 2013-08-20 08:28:31, 4 stars, 4 forks

    TV4/Urushiol:
      Test framework written in Ruby to test varnish-cache routing and caching logic
       8 commits, last change: 2013-09-20 04:21:18, 0 stars, 0 forks

    varnish/libvmod-curl:
      cURL bindings for Varnish through the Varnish Module interface
       79 commits, last change: 2013-09-05 01:31:45, 20 stars, 15 forks

    varnish/libvmod-var:
      Variable support VMOD
       43 commits, last change: 2013-04-30 01:35:06, 15 stars, 6 forks

    varnish/newrelic_varnish_plugin:
      Integration plugin between Varnish and New Relic
       20 commits, last change: 2013-07-10 04:40:33, 7 stars, 8 forks

    varnish/vagent2:
      With a license to ... err.. manage Varnish
       387 commits, last change: 2013-09-18 07:58:59, 72 stars, 11 forks

    varnish/Varnish-Book:
      Varnish Tutorial and training material
       323 commits, last change: 2013-07-08 07:13:17, 69 stars, 17 forks

    varnish/varnishgather:
      Information gathering tool for Varnish
       35 commits, last change: 2013-09-10 22:56:06, 11 stars, 2 forks

    vimeo/libvmod-boltsort:
      A fast Varnish module for sorting query string parameters.
       4 commits, last change: 2013-06-07 13:25:14, 19 stars, 3 forks

    xcir/libvmod-backendutils:
      Dynamic backend
       4 commits, last change: 2013-02-03 03:50:32, 1 stars, 0 forks

    xcir/libvmod-ldap:
      LDAP module for Varnish
       23 commits, last change: 2012-10-22 09:47:01, 7 stars, 0 forks

    xcir/libvmod-parsereq:
      parsing post,get,cookie data
       98 commits, last change: 2013-08-04 10:26:32, 18 stars, 6 forks

    xcir/vsltrans:

       14 commits, last change: 2013-06-24 08:14:21, 4 stars, 1 forks
<!-- PROJECTS_LIST_END -->
