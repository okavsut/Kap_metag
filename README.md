

<!DOCTYPE html>
<html ng-app="app">
    <head>
        <meta charset="utf-8">
        <meta name="google" content="notranslate">
        <title>KAP</title>
        <meta http-equiv="X-UA-Compatible" content="IE=edge,chrome=1">
        <base href="https://www.kap.org.tr" />
        <meta name="viewport" content="width=device-width, initial-scale=1">
        <link rel="shortcut icon" type="image/x-icon" href='/assets/images/kap-favico.png'>
        <link rel="apple-touch-icon" href='/assets/images/kap-favico-L.png'>
        <meta name="format-detection" content="telephone=no">
        <link rel="alternate" hreflang="tr" href="/tr/" />
        <link rel="alternate" hreflang="en" href="/en/" />
        <link rel="alternate" href="/" hreflang="x-default" />

        <link rel="stylesheet" type="text/css" href='/assets/stylesheets/bundle.min.css?b=2068' >
        <script src='/assets/javascripts/thirdparty.min.js?b=2068'></script>
        <script type="text/javascript">
            $(window).load(function() {
                $(".loader222").fadeOut("slow");
            });

            var currentLanguageCode = "tr";
            var atLeast3CharactersRequired = "En az 3 karakter giriniz!";
            function PrintPage ( ) {
                jQuery ( '#disclosureContent' ).printArea ('disclosure') ;
            }

            function PrintGeneral (purposeString) {
                jQuery ('#printAreaDiv').printArea(purposeString);
            }

            function openSubMenu() {
                return false;
            }
        </script>
<!--[if lt IE 9]>
        <script src='/assets/javascripts/html5.js?b=2068' type="text/javascript"></script>
<![endif]-->
<!--[if lte IE 8]>
          <script type="text/javascript">
            document.createElement('ng-include');
            document.createElement('ng-pluralize');
            document.createElement('ng-view');
            document.createElement('ng:include');
            document.createElement('ng:pluralize');
            document.createElement('ng:view');
          </script>
        <![endif]-->
    </head>
    <body ng-cloak>
        <div class="loader222"></div>
        

<div style="expand-view-container">
    <div class="expand-view">
        <div class="panner-container">
            <div class="panner panLeft" data-scroll-modifier='-1'><img src="/assets/images/view_pan_left.png"></div>
            <div class="panner expand-point"><img class="expand-point-img" src="/assets/images/view_expand.png"></div>
            <div class="panner panRight" data-scroll-modifier='1'><img src="/assets/images/view_pan_right.png"></div>
        </div>
    </div>
</div>

        <div class="smartbanner" id="mobile-smartbanner" style="display: none;background-color: #d9d9dd;">
            <div class="smartbanner-container">
                <a href="#" id="smb-close" class="smartbanner-close">&times;</a>
                <img class="smartbanner-icon" src='/assets/images/kap-mobil-icon_1.png'/>
                <div class="smartbanner-info">
                    <div class="smartbanner-title">KAP Mobil</div>
                    <div id="smartbanner-title_android" style="display: none;">Android Uygulaması</div>
                    <div id="smartbanner-title_ios" style="display: none;">IOS Uygulaması</div>
                    <div id="smartbanner-title_chrome" style="display: none;">Test Chrome Uygulaması</div>
                </div>
                <a id="redirect-store" href="https://play.google.com/" target="_blank" class="smartbanner-button">
                    <span class="smartbanner-button-text">Görüntüle</span>
                </a>
            </div>
        </div>

        <div class="w-section header-section">
            <div class="rightmenu">
                <a class="w-inline-block rightmenu-image" href="javascript:void(0);">
                    <img src='/assets/images/RightMenu.png' width="27">
                </a>
                <div class="rightmenu-subblock">
                    <a class="rightmenu-item" href="http://egk.mkk.com.tr" id="rightMenueGenelKurul">e-Genel Kurul</a>
                    <a class="rightmenu-item" href="http://e-sirket.mkk.com.tr" id="rightMenueSirket">e-Şirket</a>
                    <a class="rightmenu-item" href="http://www.mkk.com.tr" id="rightMenuMkk">Merkezi Kayıt Kuruluşu</a>
                    
                    <a class="rightmenu-item" href="https://eyatirimci.mkk.com.tr/auth/login" id="rightMenuCapital">Sermaye Piyasası Aracı Alım Satım Bildirimi</a>
                </div>
            </div>
            <div class="w-container">
                <div class="header-menu-section">
                    <a class="bi-black header-toplinks type-small-en" href='/en/'>English</a>
                </div>
            </div>

            <div class="w-nav header-navbar" data-collapse="medium" data-animation="default" data-duration="400" data-contain="1">
                <div class="w-container header-container">
                    <a class="w-nav-brand w-clearfix a-kap-logo" href="/tr/">
                        
                            <img class="header-logo img-kap-logo" src='/assets/images/kap-logo.png' width="141">
                        
                    </a>
                    <div class="w-nav-button header-menubutton">
                        <div class="w-icon-nav-menu"></div>
                    </div>
                    <div class="middle-header-elements">
                    <nav class="w-nav-menu w-clearfix header-menu on" role="navigation">
                        

    
            
                <div class="menuitem"><a class="w-nav-link type-small bi-dim-gray header-divider header-menuitem" href="javascript:void(0);" onclick="openSubMenu();"  id="menu0">Bildirim Sorguları</a>
                    <div class="submenu-block">
                    

    
            
                <a class="submenu-item" href="/tr/today" id="submenu02010">Bugün Gelen Bildirimler</a>
            
        

    
            
                <a class="submenu-item" href="/tr/beklenen-bildirim-sorgu" id="submenu02120">Beklenen Bildirimler</a>
            
        

    
            
                <a class="submenu-item" href="/tr/bildirim-sorgu" id="submenu02230">Detaylı Sorgulama</a>
            
        

    
            
                <a class="submenu-item" href="/tr/kalem-karsilastirma" id="submenu02340">Finansal Tablo Kalem Sorgulama</a>
            
        


                    </div>
                </div>
            
        

    
            
                <div class="menuitem"><a class="w-nav-link type-small bi-dim-gray header-divider header-menuitem" href="javascript:void(0);" onclick="openSubMenu();"  id="menu1">Şirketler</a>
                    <div class="submenu-block">
                    

    
            
                <a class="submenu-item" href="/tr/bist-sirketler" id="submenu0201">BIST Şirketleri</a>
            
        

    
            
                <a class="submenu-item" href="/tr/sirketler/YK" id="submenu0212">Yatırım Kuruluşları</a>
            
        

    
            
                <a class="submenu-item" href="/tr/sirketler/PYS" id="submenu0223">Portföy Yönetim Şirketleri</a>
            
        

    
            
                <a class="submenu-item" href="/tr/sirketler/BDK" id="submenu0234">Bağımsız Denetim Kuruluşları</a>
            
        

    
            
                <a class="submenu-item" href="/tr/sirketler/DCS" id="submenu0245">Derecelendirme Şirketleri</a>
            
        

    
            
                <a class="submenu-item" href="/tr/sirketler/DS" id="submenu0256">Değerleme Şirketleri</a>
            
        

    
            
                <a class="submenu-item" href="/tr/sirketler/DK" id="submenu0267">Diğer KAP Üyeleri ve İşlem Görmeyen Şirketler</a>
            
        

    
            
                <a class="submenu-item" href="/tr/sirketler/KSE" id="submenu0278">KAP Üyeliği Sona Eren Şirketler</a>
            
        


                    </div>
                </div>
            
        

    
            
                <div class="menuitem"><a class="w-nav-link type-small bi-dim-gray header-divider header-menuitem" href="javascript:void(0);" onclick="openSubMenu();"  id="menu2">Fonlar</a>
                    <div class="submenu-block">
                    

    
            
                <a class="submenu-item" href="/tr/YatirimFonlari/BYF" id="submenu02010">Borsa Yatırım Fonları</a>
            
        

    
            
                <a class="submenu-item" href="/tr/YatirimFonlari/YF" id="submenu02120">Yatırım Fonları</a>
            
        

    
            
                <a class="submenu-item" href="/tr/YatirimFonlari/EYF" id="submenu02230">Emeklilik Yatırım Fonları</a>
            
        

    
            
                <a class="submenu-item" href="/tr/YatirimFonlari/OKS" id="submenu02335">OKS Emeklilik Yatırım Fonları</a>
            
        

    
            
                <a class="submenu-item" href="/tr/YatirimFonlari/YYF" id="submenu02440">Yabancı Yatırım Fonları</a>
            
        

    
            
                <a class="submenu-item" href="/tr/YatirimFonlari/VFF" id="submenu02550">Varlık Finansman Fonları</a>
            
        

    
            
                <a class="submenu-item" href="/tr/YatirimFonlari/KFF" id="submenu02660">Konut Finansman Fonları</a>
            
        

    
            
                <a class="submenu-item" href="/tr/YatirimFonlari/GMF" id="submenu02770">Gayrimenkul Yatırım Fonları</a>
            
        

    
            
                <a class="submenu-item" href="/tr/YatirimFonlari/GSF" id="submenu02880">Girişim Sermayesi Yatırım Fonları</a>
            
        

    
            
                <a class="submenu-item" href="/tr/YatirimFonlari/PFF" id="submenu02985">Proje Finansman Fonları</a>
            
        

    
            
                <a class="submenu-item" href="/tr/YatirimFonlari/TEYF" id="submenu021090">Tasfiye Olmuş Fonlar</a>
            
        


                    </div>
                </div>
            
        

    
            
                <div class="menuitem"><a class="w-nav-link type-small bi-dim-gray header-menuitem" href="javascript:void(0);" onclick="openSubMenu();" id="menu-block3">KAP Hakkında</a>
                    <div class="submenu-block">
                    

    
            
                <a class="submenu-item" href="/tr/menu-icerik/KAP-Hakkinda/Mevzuat-Duyurular-ve-Kilavuzlar" id="submenu01">Mevzuat, Duyurular ve Kılavuzlar</a>
            
        

    
            
                <a class="submenu-item" href="/tr/menu-icerik/KAP-Hakkinda/Sertifika-Islemleri" id="submenu120">Sertifika İşlemleri</a>
            
        

    
            
                <a class="submenu-item" href="/tr/menu-icerik/KAP-Hakkinda/Genel-Bilgi" id="submenu230">Genel Bilgi</a>
            
        

    
            
                <a class="submenu-item" href="/tr/menu-icerik/KAP-Hakkinda/Ilgili-Linkler" id="submenu360">İlgili Linkler</a>
            
        

    
            
                <a class="submenu-item" href="https://eyatirimci.mkk.com.tr/auth/login" id="submenu470">Sermaye Piyasası Aracı Alım Satım Bildirimi</a>
            
        

    
            
                <a class="submenu-item" href="/tr/menu-icerik/KAP-Hakkinda/KVKK-Kapsaminda-Duzeltilmis-Bildirimler" id="submenu580">KVKK Kapsamında Düzeltilmiş Bildirimler</a>
            
        


                    </div>
                </div>
            
        


                    </nav>
                    </div>
                        
                        <a href="https://www.mkk.com.tr" target="_blank">
                            <img class="img-mkk-logo" src='/assets/images/merkezi-kayit-istanbul-logo.png'>
                        </a>
                        
                </div>
            </div>
        </div>

        <div id="search-container" class="w-container" style="position:relative">
            <form class="w-section searchbar-section" onsubmit="startSearch(keywords.value, categories.value,30)" style="margin-bottom: 0px !important;">
                <select class="filter-multi2" name="categories" id="categories">
                    <option value="ALL">Tüm Kategoriler</option>
                    <option value="ODA">Özel Durum Açıklaması</option>
                    <option value="FR">Finansal Rapor</option>
                    
                    <option value="DG">Diğer Bildirimler</option>
                    <option value="FON">Fon Bildirimleri</option>
                </select>
                <input id="searchInput" name="keywords" class="filter-inputbox w-input" placeholder="Arama Yapınız..." style="margin-bottom: 0px !important; padding: 10px;" />
                <div type="submit" class="search-button" onclick="startSearch(document.getElementById('searchInput').value, document.getElementById('categories').value,30)">
                    <img src="/assets/images/Header_Search.png" />
                </div>
                <input type="hidden" name="as_fid" value="b2abc50440edbd54b50f80ec0f06d3a3de961eee" autocomplete="off">
            <input type="hidden" name="as_fid" value="45415ea2c9b2c55a086a9fd817488fc6581d924e" /></form>
            <div id="searchDivId" class="header-search-div" style="opacity: 0">
            </div>
        </div>

        <div class="w-section banner-section">
            <div class="w-slider banner-slider" data-autoplay="-1" data-animation="cross" data-delay="7777" data-duration="500" data-infinite="1" data-easing="ease-in-out">
                <div class="w-slider-mask banner-mask" data-step="1"  data-intro="Kamu Aydınlatma Platformu Yeni haliyle karşınızda">
                    
                        
                            <div class="w-slide banner-slide" style="cursor: pointer; background-size: cover;background-position: 50% 50%;background-image: url('/tr/file/Banner/Banner-5')" onclick="window.open('https://www.vap.org.tr/donemsel-finansal-oranlar','new_window');" >
                        
                            <div class="w-container">
                                    <div class="banner-title"></div>
                                    <h1 class="banner-header"></h1>
                            </div>
                        </div>
                    
                        
                            <div class="w-slide banner-slide" style="cursor: pointer; background-size: cover;background-position: 50% 50%;background-image: url('/tr/file/Banner/Banner-1')" onclick="window.open('https://www.vap.org.tr/','new_window');" >
                        
                            <div class="w-container">
                                    <div class="banner-title"></div>
                                    <h1 class="banner-header"></h1>
                            </div>
                        </div>
                    
                        
                            <div class="w-slide banner-slide" style="cursor: pointer; background-size: cover;background-position: 50% 50%;background-image: url('/tr/file/Banner/Banner-2')" onclick="window.open('https://eyatirimci.mkk.com.tr/auth/login','new_window');" >
                        
                            <div class="w-container">
                                    <div class="banner-title"></div>
                                    <h1 class="banner-header"></h1>
                            </div>
                        </div>
                    
                        
                            <div class="w-slide banner-slide" style="cursor: pointer; background-size: cover;background-position: 50% 50%;background-image: url('/tr/file/Banner/Banner-3')" onclick="window.open('https://www.vap.org.tr/','new_window');" >
                        
                            <div class="w-container">
                                    <div class="banner-title"></div>
                                    <h1 class="banner-header"></h1>
                            </div>
                        </div>
                    
                        
                            <div class="w-slide banner-slide" style="background-size: cover;background-position: 50% 50%;background-image: url('/tr/file/Banner/Banner-4')">
                        
                            <div class="w-container">
                                    <div class="banner-title"></div>
                                    <h1 class="banner-header"></h1>
                            </div>
                        </div>
                    
                    <div class="w-clearfix banner-minimize-box banner-minimize-forClick">
                        <a class="w-inline-block banner-minimize" href="#">
                            <img src="/assets/images/Banner_Minimize.png" width="35">
                        </a>
                        <a class="w-inline-block banner-maximize" href="#">
                            <img src="/assets/images/Banner_Maximize.png" width="35">
                        </a>
                    </div>
                </div>
                <div class="w-slider-arrow-left banner-left">
                    <div class="w-icon-slider-left banner-left-icon"></div>
                </div>
                <div class="w-slider-arrow-right banner-right">
                    <div class="w-icon-slider-right banner-right-icon"></div>
                </div>
                <div class="w-slider-nav banner-nav">
                    <div class="w-slider-dot w-active" data-wf-ignore=""></div>
                    <div class="w-slider-dot" data-wf-ignore=""></div>
                </div>
            </div>
        </div>
        <div class="w-section middle-section">
            <div class="w-container middle-container">
            
<script>
    function printPage(){
      var frameCount = 1 ;
      var disclosureIndex = '466156';
      var x = document.createElement("iframe");
      x.id = "printFrame";
      x.src='/tr/BildirimCokluPdf/' + disclosureIndex;
      document.body.appendChild(x);
      setTimeout(function(){window.frames[window.frames.length-1].print()},2000);
      setTimeout(function(){window.frames["printFrame"].remove()},8000);
    }
</script>
<div style="clear : both"></div>

    <div id="disclosureContent">
        
        <div class="w-clearfix modal-single disc-type-dg disc-class-dg" ng-controller="DisclosureCtrl" ng-init="disclosureIndex = 466156">
            <div class="modal-headerleft">
                <img src="/SirketLogo/402821824bf524dd014c9de5bd6500e4" width="100px" onerror="this.src='/assets/images/no_logo.png'" />
            </div>
            <div class="modal-headertext">
                
                    
                        
                            <div class="type-medium type-bold bi-sky-black"><a href="/tr/sirket-bilgileri/ozet/2446-metag-insaat-ticaret-a-s">METAG İNŞAAT TİCARET A.Ş.</a></div>
                        
                    
                
            <div class="type-medium bi-dim-gray">MTGAS</div>
            </div>
            <div class="w-clearfix modal-headerright">
                
                
                
                
                
            </div>
            <div class="w-clearfix modal-attachments">
                <a class="modal-attachmaximize maximize" href="#">Ekleri Gör</a>
                
                
            </div>
            <div class="modal-brief">
                
            <a class="modal-briefbutton relatedDisclosure" ng-click="openDisclosureModal([[]], 'tr')" href="#" ng-show="false">Düzeltilmiş Bildirim</a>
                
                    <a class="modal-briefbutton type-small not" href="/tr/bildirim-sorgu?member=402821824bf524dd014c9de5bd6500e4">Bildirimler</a>
                    <a class="modal-briefbutton fin type-small" href="/tr/bildirim-sorgu?member=402821824bf524dd014c9de5bd6500e4&disclosureClass=FR">Finansal Tablolar</a>
                    <a class="modal-briefbutton cal type-small" href="/tr/filterCaCalendar/402821824bf524dd014c9de5bd6500e4/METAG İNŞAAT TİCARET A.Ş.">Hak Kullanımları</a>
                
            <div class="w-row modal-briefsummary">
                <div class="w-col w-col-3 modal-briefsumcol">
                    <div class="type-small bi-lightgray">Gönderim Tarihi</div>
                    <div class="type-medium bi-sky-black">11.12.2024 15:33:38</div>
                </div>
                <div class="w-col w-col-3 modal-briefsumcol">
                    <div class="type-small bi-lightgray">Bildirim Tipi</div>
                    <div class="type-medium bi-sky-black">
                    
                        DG
                    
                    </div>
                </div>
                <div class="w-col w-col-3 modal-briefsumcol">
                    <div class="type-small bi-lightgray">Yıl</div>
                    <div class="type-medium bi-sky-black">-</div>
                </div>
                <div class="w-col w-col-3 modal-briefsumcol">
                    <div class="type-small bi-lightgray">Periyot</div>
                    <div class="type-medium bi-sky-black">-</div>
                </div>
            </div>
            </div>
            <div class="modal-info">
            
                <h1>
                    Transfer Görüşmeleri
                    <div class="font-resize">
                        <a href="#" class="font-resize-big" alt="İçeriği büyült"><span>A</span><sup>+</sup></a>
                        <a href="#" class="font-resize-small" alt="İçeriği küçült"><span>A</span><sup>-</sup></a>
                    </div>
                </h1>
                
                    <div class="disclosureScrollableArea oldKap">
                    
                        <div>   
 <span><br><br><a name="bdsgorusu_466156" href="javascript:;"></a><br></span> 
 <span class="baslikbildirim"><br> &nbsp;&nbsp;Özet Bilgi<br></span> 
 <span> <br> 
  <table border="1" cellpadding="2" cellspacing="0" style="border-collapse: collapse" bordercolor="#5198B9"> 
   <tbody> 
    <tr> 
     <td colspan="6" bgcolor="#F8F9FA"></td> 
    </tr> 
    <tr> 
     <td><b>1</b> </td> 
     <td style="padding-right: 10px;">ALPER AYATA </td> 
     <td style="padding-right: 10px;">Beton Santralinden Sorumlu İnşaat Mühendisi </td> 
     <td style="padding-right: 10px;">METAG İNŞAAT TİCARET A.Ş. </td> 
     <td style="padding-right: 10px;">11.12.2024 15:32:05 </td> 
    </tr> 
   </tbody> 
  </table></span> 
 <span class="basliktablometin"><br> &nbsp;&nbsp;<br></span> 
 <table class="tablob" cellspacing="0" cellpadding="1" rules="all" border="1"> 
  <tbody> 
   <tr class="tablobaslikb" align="left"> 
    <td class="tablobaslikb">Transfer Görüşmeleri</td>
    <td class="tablobaslikb">Açıklama</td>
   </tr> 
   <tr class="tablohucreb" align="left"> 
    <td class="tablohucreb">Yapılan Açıklama Güncelleme mi?</td> 
    <td class="tablohucreb">Hayır</td>
   </tr> 
   <tr class="tablohucre2b" align="left"> 
    <td class="tablohucre2b">Yapılan Açıklama Düzeltme mi?</td> 
    <td class="tablohucre2b">Hayır</td> 
   </tr> 
   <tr class="tablohucreb" align="left"> 
    <td class="tablohucreb">Konuya İlişkin Daha Önce Yapılan Açıklamanın Tarihi</td> 
    <td class="tablohucreb">-</td> 
   </tr> 
   <tr class="tablohucreb" align="left"> 
    <td class="tablohucreb">Yapılan Açıklama Ertelenmiş Bir Açıklama mı?</td> 
    <td class="tablohucreb">Hayır</td> 
    </tr> 
   <tr class="tablohucreb" align="left"> 
    <td class="tablohucreb">Transfer Görüşmelerine Konu Kişinin Adı-Soyadı</td> 
    <td class="tablohucreb">Alper Ayata</td> 
    </tr> 
   <tr class="tablohucreb" align="left"> 
    <td class="tablohucreb">Transfer Görüşmelerine Konu Kişinin Bağlı Bulunduğu Firma</td> 
    <td class="tablohucreb">Zn Elektrik </td> 
    </tr> 
   <tr class="tablohucreb" align="left"> 
    <td class="tablohucreb">Transfer Şekli</td> 
    <td class="tablohucreb">Satın Alma </td> 
    </tr> 
  </tbody> 
 </table> 
</div>
                        <br />
                    
                    </div>
                
            
            </div>
        </div>
    
    </div>
    
            <div class="w-clearfix modal-buttons">
                
                    <a class="modal-button _4 type-small" href="javascript:PrintPage();">Yazdır</a>
                

            </div>
        


<br />

            </div>
        </div>
        <div class="w-section footer-section">
            
                <div class="footer-buttons">
                    <div class="w-container">
                        <a class="w-inline-block footer-button first" target="_blank" href="https://www.vap.org.tr/">
                            <div class="type-small bi-sky-black">Veri Analiz Platformu </div>
                        </a>
                        <a class="w-inline-block footer-button forth" target="_blank" href="https://eyatirimci.mkk.com.tr/auth/login">
                            <div class="type-small bi-sky-black">Yatırımcı Bilgi Merkezi</div>
                        </a>
                        <a class="w-inline-block footer-button second" target="_blank" href="https://www.borsaistanbul.com/tr/sayfa/477/gunluk-bulten">
                            <div class="type-small bi-sky-black">Borsa Günlük Bülteni</div>
                        </a>
                        <a class="w-inline-block footer-button third" target="_blank" href="http://www.spk.gov.tr/Bulten">
                            <div class="type-small bi-sky-black">SPK Bülteni</div>
                        </a>
                        <a class="w-inline-block footer-button fifth" target="_blank" href="https://gms.kap.org.tr">
                            <div class="type-small bi-sky-black">Gayrimenkul Sertifikaları</div>
                        </a>
                    </div>
                </div>
            
            <div class="footer-links">
                <div class="w-container">
                    <div class="w-row padding bottom kapstyle3">

                    
                        <div class="w-col w-col-3">
                            <div class="bi-lightgray type-medium">Bildirim Sorguları</div>
                        </div>
                    
                        <div class="w-col w-col-3">
                            <div class="bi-lightgray type-medium">Şirketler</div>
                        </div>
                    
                        <div class="w-col w-col-3">
                            <div class="bi-lightgray type-medium">Fonlar</div>
                        </div>
                    
                        <div class="w-col w-col-3">
                            <div class="bi-lightgray type-medium">KAP Hakkında</div>
                        </div>
                    

                    </div>
                    <div class="w-row type-xsmall kapstyle4">
                    
                        
                            <div class="w-col w-col-3">
                            
                                
                                    
                                            
                                                <a class="type-expand bi-white padding bottom small" href="/tr/today">Bugün Gelen Bildirimler</a>
                                            
                                        
                                
                                    
                                            
                                                <a class="type-expand bi-white padding bottom small" href="/tr/beklenen-bildirim-sorgu">Beklenen Bildirimler</a>
                                            
                                        
                                
                                    
                                            
                                                <a class="type-expand bi-white padding bottom small" href="/tr/bildirim-sorgu">Detaylı Sorgulama</a>
                                            
                                        
                                
                                    
                                            
                                                <a class="type-expand bi-white padding bottom small" href="/tr/kalem-karsilastirma">Finansal Tablo Kalem Sorgulama</a>
                                            
                                        
                                
                            
                            </div>
                        
                    
                        
                            <div class="w-col w-col-3">
                            
                                
                                    
                                            
                                                <a class="type-expand bi-white padding bottom small" href="/tr/bist-sirketler">BIST Şirketleri</a>
                                            
                                        
                                
                                    
                                            
                                                <a class="type-expand bi-white padding bottom small" href="/tr/sirketler/YK">Yatırım Kuruluşları</a>
                                            
                                        
                                
                                    
                                            
                                                <a class="type-expand bi-white padding bottom small" href="/tr/sirketler/PYS">Portföy Yönetim Şirketleri</a>
                                            
                                        
                                
                                    
                                            
                                                <a class="type-expand bi-white padding bottom small" href="/tr/sirketler/BDK">Bağımsız Denetim Kuruluşları</a>
                                            
                                        
                                
                                    
                                            
                                                <a class="type-expand bi-white padding bottom small" href="/tr/sirketler/DCS">Derecelendirme Şirketleri</a>
                                            
                                        
                                
                                    
                                            
                                                <a class="type-expand bi-white padding bottom small" href="/tr/sirketler/DS">Değerleme Şirketleri</a>
                                            
                                        
                                
                                    
                                            
                                                <a class="type-expand bi-white padding bottom small" href="/tr/sirketler/DK">Diğer KAP Üyeleri ve İşlem Görmeyen Şirketler</a>
                                            
                                        
                                
                                    
                                            
                                                <a class="type-expand bi-white padding bottom small" href="/tr/sirketler/KSE">KAP Üyeliği Sona Eren Şirketler</a>
                                            
                                        
                                
                            
                            </div>
                        
                    
                        
                            <div class="w-col w-col-3">
                            
                                
                                    
                                            
                                                <a class="type-expand bi-white padding bottom small" href="/tr/YatirimFonlari/BYF">Borsa Yatırım Fonları</a>
                                            
                                        
                                
                                    
                                            
                                                <a class="type-expand bi-white padding bottom small" href="/tr/YatirimFonlari/YF">Yatırım Fonları</a>
                                            
                                        
                                
                                    
                                            
                                                <a class="type-expand bi-white padding bottom small" href="/tr/YatirimFonlari/EYF">Emeklilik Yatırım Fonları</a>
                                            
                                        
                                
                                    
                                            
                                                <a class="type-expand bi-white padding bottom small" href="/tr/YatirimFonlari/OKS">OKS Emeklilik Yatırım Fonları</a>
                                            
                                        
                                
                                    
                                            
                                                <a class="type-expand bi-white padding bottom small" href="/tr/YatirimFonlari/YYF">Yabancı Yatırım Fonları</a>
                                            
                                        
                                
                                    
                                            
                                                <a class="type-expand bi-white padding bottom small" href="/tr/YatirimFonlari/VFF">Varlık Finansman Fonları</a>
                                            
                                        
                                
                                    
                                            
                                                <a class="type-expand bi-white padding bottom small" href="/tr/YatirimFonlari/KFF">Konut Finansman Fonları</a>
                                            
                                        
                                
                                    
                                            
                                                <a class="type-expand bi-white padding bottom small" href="/tr/YatirimFonlari/GMF">Gayrimenkul Yatırım Fonları</a>
                                            
                                        
                                
                                    
                                            
                                                <a class="type-expand bi-white padding bottom small" href="/tr/YatirimFonlari/GSF">Girişim Sermayesi Yatırım Fonları</a>
                                            
                                        
                                
                                    
                                            
                                                <a class="type-expand bi-white padding bottom small" href="/tr/YatirimFonlari/PFF">Proje Finansman Fonları</a>
                                            
                                        
                                
                                    
                                            
                                                <a class="type-expand bi-white padding bottom small" href="/tr/YatirimFonlari/TEYF">Tasfiye Olmuş Fonlar</a>
                                            
                                        
                                
                            
                            </div>
                        
                    
                        
                            <div class="w-col w-col-3">
                            
                                
                                    
                                            
                                                <a class="type-expand bi-white padding bottom small" href="/tr/menu-icerik/KAP-Hakkinda/Mevzuat-Duyurular-ve-Kilavuzlar">Mevzuat, Duyurular ve Kılavuzlar</a>
                                            
                                        
                                
                                    
                                            
                                                <a class="type-expand bi-white padding bottom small" href="/tr/menu-icerik/KAP-Hakkinda/Sertifika-Islemleri">Sertifika İşlemleri</a>
                                            
                                        
                                
                                    
                                            
                                                <a class="type-expand bi-white padding bottom small" href="/tr/menu-icerik/KAP-Hakkinda/Genel-Bilgi">Genel Bilgi</a>
                                            
                                        
                                
                                    
                                            
                                                <a class="type-expand bi-white padding bottom small" href="/tr/menu-icerik/KAP-Hakkinda/Ilgili-Linkler">İlgili Linkler</a>
                                            
                                        
                                
                                    
                                            
                                                <a class="type-expand bi-white padding bottom small" href="https://eyatirimci.mkk.com.tr/auth/login">Sermaye Piyasası Aracı Alım Satım Bildirimi</a>
                                            
                                        
                                
                                    
                                            
                                                <a class="type-expand bi-white padding bottom small" href="/tr/menu-icerik/KAP-Hakkinda/KVKK-Kapsaminda-Duzeltilmis-Bildirimler">KVKK Kapsamında Düzeltilmiş Bildirimler</a>
                                            
                                        
                                
                            
                            </div>
                        
                    

                    </div>
                    <div class="padding bottom top">
                        <div class="bi-lightgray type-medium kapstyle3">İlgili Bağlantılar</div>
                    </div>

                    <div class="bi-white type-xsmall"  >
                        <span class="padding right medium"><a class="footermenu-item" target="_blank" href="http://egk.mkk.com.tr" id="footerMenu1">e-Genel Kurul</a> </span>
                        <span class="padding right medium"><a class="footermenu-item" target="_blank" href="https://eyatirimci.mkk.com.tr/auth/login" id="footerMenu2">e-Yatırımcı</a></span>
                        <span class="padding right medium"><a class="footermenu-item" target="_blank" href="http://e-sirket.mkk.com.tr" id="footerMenu3">e-Şirket</a></span>
                        <span class="padding right medium"><a class="footermenu-item" target="_blank" href='https://www.mkk.com.tr/tr-tr/Veri-Depolama-Hizmetleri/e-VERi/Sayfalar/Yillik-Istatistiki-Veriler.aspx' id="footerMenu4">e-Veri</a></span>
                        <span class="padding right medium"><a class="footermenu-item" target="_blank" href="http://www.borsaistanbul.com" id="footerMenu6">Borsa İstanbul A.Ş.</a> </span>
                        <span class="padding right medium"><a class="footermenu-item" target="_blank" href="https://www.vap.org.tr/Sayfalar/home.aspx" id="footerMenu7">VAP</a> </span>
                    </div>
                </div>
            </div>
            <a href="javascript:void(0);" class="back-to-top">Yukarı</a>
            <div class="footer-bottom">
                <div class="w-container">
                    <img class="footer-logo" src='/assets/images/Footer_Logo.png' />
                    <div class="footer-middle-elems">
                    <a class="bi-white footer-bottomlinks type-small" href='/tr/icerik/Diger/Site-Haritasi'>
                        Site Haritası
                    </a>
                    <a class="bi-white footer-bottomlinks type-small" href='/tr/icerik/Diger/Iletisim'>
                        İletişim
                    </a>
                    <a class="bi-white footer-bottomlinks type-small" href='/tr/icerik/Diger/Yardim'>
                        Yardım
                    </a>
                    <a class="bi-white footer-bottomlinks type-small" href='/tr/icerik/Diger/Kisisel-Verilerin-Korunmasi'>
                        Kişisel Verilerin Korunması
                    </a>
                    <a class="bi-white footer-bottomlinks type-small" href='/tr/icerik/Diger/Telif-Hakki-ve-Cekince-Bildirimi'>
                        Telif Hakkı ve Çekince İhbarı
                    </a>
                    </div>
                    <img class="mkk-footer-logo" src='/assets/images/mkk-footer.png' />
                </div>
            </div>
        </div>

        <script type="text/javascript" src='/assets/javascripts/angular_bundle.min.js?b=2068'></script>
        <script type="text/javascript" src='/assets/javascripts/thirdparty_extended.min.js?b=2068'></script>
        
        
    
        <script type="text/javascript" src='/assets/javascripts/bundle.min.js?b=2068'></script>
    
<!--[if lte IE 9]><script type="text/javascript" src='/assets/javascripts/placeholders.min.js?b=2068'></script><![endif]-->

    <script type="text/javascript" src='/assets/javascripts/custom2.min.js?b=2068'></script>
    
        <script async src="https://www.googletagmanager.com/gtag/js?id=G-MBNFVK7SX4"></script>
        <script>
                window.dataLayer = window.dataLayer || [];
                function gtag(){dataLayer.push(arguments);}
                gtag('js', new Date());
                gtag('config', 'G-MBNFVK7SX4',
                        {
                            //'page_title' : 'Sayfa Başlığı', // opsiyonel
                            'page_location': window.location.href, // opsiyonel
                            'page_path': location.pathname
                        });
                gtag('event', 'screen_view', {
                    'app_name': 'KAP'
                });
        </script>
    
    </body>
</html>
