<!DOCTYPE html>
<html>
<head>
    
    <meta http-equiv="content-type" content="text/html; charset=UTF-8" />
    
        <script>
            L_NO_TOUCH = false;
            L_DISABLE_3D = false;
        </script>
    
    <style>html, body {width: 100%;height: 100%;margin: 0;padding: 0;}</style>
    <style>#map {position:absolute;top:0;bottom:0;right:0;left:0;}</style>
    <script src="https://cdn.jsdelivr.net/npm/leaflet@1.6.0/dist/leaflet.js"></script>
    <script src="https://code.jquery.com/jquery-1.12.4.min.js"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.2.0/js/bootstrap.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/Leaflet.awesome-markers/2.0.2/leaflet.awesome-markers.js"></script>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/leaflet@1.6.0/dist/leaflet.css"/>
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.2.0/css/bootstrap.min.css"/>
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.2.0/css/bootstrap-theme.min.css"/>
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/font-awesome/4.6.3/css/font-awesome.min.css"/>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/Leaflet.awesome-markers/2.0.2/leaflet.awesome-markers.css"/>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/python-visualization/folium/folium/templates/leaflet.awesome.rotate.min.css"/>
    
            <meta name="viewport" content="width=device-width,
                initial-scale=1.0, maximum-scale=1.0, user-scalable=no" />
            <style>
                #map_dd4c0c7827ccc72813be92400204383d {
                    position: relative;
                    width: 100.0%;
                    height: 100.0%;
                    left: 0.0%;
                    top: 0.0%;
                }
            </style>
        
</head>
<body>
    
    
    <h3 align="center" style="font-size:20px"><b>World CO<sub>2</sub> Emissions Map (2020)</b></h3>
    
            <div class="folium-map" id="map_dd4c0c7827ccc72813be92400204383d" ></div>
        
</body>
<script>
    
    
            var map_dd4c0c7827ccc72813be92400204383d = L.map(
                "map_dd4c0c7827ccc72813be92400204383d",
                {
                    center: [20.0, 0.0],
                    crs: L.CRS.EPSG3857,
                    zoom: 2,
                    zoomControl: true,
                    preferCanvas: false,
                }
            );

            

        
    
            var tile_layer_cf6031f9931725418644e1195496ed22 = L.tileLayer(
                "https://{s}.tile.openstreetmap.org/{z}/{x}/{y}.png",
                {"attribution": "Data by \u0026copy; \u003ca href=\"http://openstreetmap.org\"\u003eOpenStreetMap\u003c/a\u003e, under \u003ca href=\"http://www.openstreetmap.org/copyright\"\u003eODbL\u003c/a\u003e.", "detectRetina": false, "maxNativeZoom": 18, "maxZoom": 18, "minZoom": 0, "noWrap": false, "opacity": 1, "subdomains": "abc", "tms": false}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
            var circle_marker_69a15e7a5178f67b31ab1b1c44f8896b = L.circleMarker(
                [33.0, 65.0],
                {"bubblingMouseEvents": true, "color": "green", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "green", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 0.446957744014136, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_f667fc20e386c19f43b48bc6f332740f = L.popup({"maxWidth": "100%"});

        
            var html_e436344dae923836d199648e0528e12d = $(`<div id="html_e436344dae923836d199648e0528e12d" style="width: 100.0%; height: 100.0%;">Afghanistan: 0.223478872007068 metric tons per capita</div>`)[0];
            popup_f667fc20e386c19f43b48bc6f332740f.setContent(html_e436344dae923836d199648e0528e12d);
        

        circle_marker_69a15e7a5178f67b31ab1b1c44f8896b.bindPopup(popup_f667fc20e386c19f43b48bc6f332740f)
        ;

        
    
    
            var circle_marker_fdf6e3626467ac79cd55c158c4f4e1c3 = L.circleMarker(
                [-12.5, 18.5],
                {"bubblingMouseEvents": true, "color": "green", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "green", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1.185485935558074, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_89efa4a013b823b51f89923a9c9880c0 = L.popup({"maxWidth": "100%"});

        
            var html_a56052c59207139d19fbae750b92f444 = $(`<div id="html_a56052c59207139d19fbae750b92f444" style="width: 100.0%; height: 100.0%;">Angola: 0.592742967779037 metric tons per capita</div>`)[0];
            popup_89efa4a013b823b51f89923a9c9880c0.setContent(html_a56052c59207139d19fbae750b92f444);
        

        circle_marker_fdf6e3626467ac79cd55c158c4f4e1c3.bindPopup(popup_89efa4a013b823b51f89923a9c9880c0)
        ;

        
    
    
            var circle_marker_e017810546b7102119450ae1666e46bc = L.circleMarker(
                [41.0, 20.0],
                {"bubblingMouseEvents": true, "color": "green", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "green", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3.08910023049148, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_77f2c879b5c339748c12b6302be53c24 = L.popup({"maxWidth": "100%"});

        
            var html_ee03a4789091a21b51a1041228d1c1fc = $(`<div id="html_ee03a4789091a21b51a1041228d1c1fc" style="width: 100.0%; height: 100.0%;">Albania: 1.54455011524574 metric tons per capita</div>`)[0];
            popup_77f2c879b5c339748c12b6302be53c24.setContent(html_ee03a4789091a21b51a1041228d1c1fc);
        

        circle_marker_e017810546b7102119450ae1666e46bc.bindPopup(popup_77f2c879b5c339748c12b6302be53c24)
        ;

        
    
    
            var circle_marker_e55bcdb57a7c1065e272512143f2668a = L.circleMarker(
                [42.5, 1.6],
                {"bubblingMouseEvents": true, "color": "orange", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "orange", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 11.55429598455598, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_abc97343f85299ac76e7eb66862bb30d = L.popup({"maxWidth": "100%"});

        
            var html_516ddb12677f958009aaca5dc202be28 = $(`<div id="html_516ddb12677f958009aaca5dc202be28" style="width: 100.0%; height: 100.0%;">Andorra: 5.77714799227799 metric tons per capita</div>`)[0];
            popup_abc97343f85299ac76e7eb66862bb30d.setContent(html_516ddb12677f958009aaca5dc202be28);
        

        circle_marker_e55bcdb57a7c1065e272512143f2668a.bindPopup(popup_abc97343f85299ac76e7eb66862bb30d)
        ;

        
    
    
            var circle_marker_8d6058df997b1a5cef078c5b0239a477 = L.circleMarker(
                [24.0, 54.0],
                {"bubblingMouseEvents": true, "color": "darkred", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "darkred", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 40.5045433602852, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_04e8528f983765a9befc40fc6295768b = L.popup({"maxWidth": "100%"});

        
            var html_77e9183b086546fa0d36d5fd5b8df151 = $(`<div id="html_77e9183b086546fa0d36d5fd5b8df151" style="width: 100.0%; height: 100.0%;">United Arab Emirates: 20.2522716801426 metric tons per capita</div>`)[0];
            popup_04e8528f983765a9befc40fc6295768b.setContent(html_77e9183b086546fa0d36d5fd5b8df151);
        

        circle_marker_8d6058df997b1a5cef078c5b0239a477.bindPopup(popup_04e8528f983765a9befc40fc6295768b)
        ;

        
    
    
            var circle_marker_85fb66f16e133a08fd32df014a9e5844 = L.circleMarker(
                [-34.0, -64.0],
                {"bubblingMouseEvents": true, "color": "yellow", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "yellow", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 6.8112350808276, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_8c3f6c8c69efbab4927bff451b127cbc = L.popup({"maxWidth": "100%"});

        
            var html_efb8f4fe9087c0a31443e52a76791d88 = $(`<div id="html_efb8f4fe9087c0a31443e52a76791d88" style="width: 100.0%; height: 100.0%;">Argentina: 3.4056175404138 metric tons per capita</div>`)[0];
            popup_8c3f6c8c69efbab4927bff451b127cbc.setContent(html_efb8f4fe9087c0a31443e52a76791d88);
        

        circle_marker_85fb66f16e133a08fd32df014a9e5844.bindPopup(popup_8c3f6c8c69efbab4927bff451b127cbc)
        ;

        
    
    
            var circle_marker_72db79e55562ab90cff953ee8a49484e = L.circleMarker(
                [40.0, 45.0],
                {"bubblingMouseEvents": true, "color": "green", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "green", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 4.80936752390212, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_3db9a7400687aa94f4e2c692732cb108 = L.popup({"maxWidth": "100%"});

        
            var html_87fe461f0a00b32eff6539099b30a323 = $(`<div id="html_87fe461f0a00b32eff6539099b30a323" style="width: 100.0%; height: 100.0%;">Armenia: 2.40468376195106 metric tons per capita</div>`)[0];
            popup_3db9a7400687aa94f4e2c692732cb108.setContent(html_87fe461f0a00b32eff6539099b30a323);
        

        circle_marker_72db79e55562ab90cff953ee8a49484e.bindPopup(popup_3db9a7400687aa94f4e2c692732cb108)
        ;

        
    
    
            var circle_marker_e19d0fcd0389d5532f23c5919caf2eff = L.circleMarker(
                [17.05, -61.8],
                {"bubblingMouseEvents": true, "color": "orange", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "orange", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 10.24346024346024, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_5bbf734a867f18860fd9b97f89e7a1be = L.popup({"maxWidth": "100%"});

        
            var html_3c905ef9e44cbddc324666ba995d6f95 = $(`<div id="html_3c905ef9e44cbddc324666ba995d6f95" style="width: 100.0%; height: 100.0%;">Antigua and Barbuda: 5.12173012173012 metric tons per capita</div>`)[0];
            popup_5bbf734a867f18860fd9b97f89e7a1be.setContent(html_3c905ef9e44cbddc324666ba995d6f95);
        

        circle_marker_e19d0fcd0389d5532f23c5919caf2eff.bindPopup(popup_5bbf734a867f18860fd9b97f89e7a1be)
        ;

        
    
    
            var circle_marker_96dbd211b95a70eaeadba156ff1047ca = L.circleMarker(
                [-27.0, 133.0],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "red", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 29.5522738132518, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_3b4b09f298eb3a4f0606a5c566452827 = L.popup({"maxWidth": "100%"});

        
            var html_a50089aaee74e4c20e808c48918cb3ff = $(`<div id="html_a50089aaee74e4c20e808c48918cb3ff" style="width: 100.0%; height: 100.0%;">Australia: 14.7761369066259 metric tons per capita</div>`)[0];
            popup_3b4b09f298eb3a4f0606a5c566452827.setContent(html_a50089aaee74e4c20e808c48918cb3ff);
        

        circle_marker_96dbd211b95a70eaeadba156ff1047ca.bindPopup(popup_3b4b09f298eb3a4f0606a5c566452827)
        ;

        
    
    
            var circle_marker_a8739c869728e923476726a0d32a1916 = L.circleMarker(
                [47.3333, 13.3333],
                {"bubblingMouseEvents": true, "color": "orange", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "orange", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 13.26529147467092, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_6840211466d543f08bb5fe4e78d30dee = L.popup({"maxWidth": "100%"});

        
            var html_f3f8a903d1b6da723fbcd878e3bcea6e = $(`<div id="html_f3f8a903d1b6da723fbcd878e3bcea6e" style="width: 100.0%; height: 100.0%;">Austria: 6.63264573733546 metric tons per capita</div>`)[0];
            popup_6840211466d543f08bb5fe4e78d30dee.setContent(html_f3f8a903d1b6da723fbcd878e3bcea6e);
        

        circle_marker_a8739c869728e923476726a0d32a1916.bindPopup(popup_6840211466d543f08bb5fe4e78d30dee)
        ;

        
    
    
            var circle_marker_6c1a215101a1dddcde99d4905f2ca7f2 = L.circleMarker(
                [40.5, 47.5],
                {"bubblingMouseEvents": true, "color": "yellow", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "yellow", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 6.79769914578454, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_a7dba9eba01acaf0123f1d6bb08dde03 = L.popup({"maxWidth": "100%"});

        
            var html_4bc52b028808559341f85880cc3ba722 = $(`<div id="html_4bc52b028808559341f85880cc3ba722" style="width: 100.0%; height: 100.0%;">Azerbaijan: 3.39884957289227 metric tons per capita</div>`)[0];
            popup_a7dba9eba01acaf0123f1d6bb08dde03.setContent(html_4bc52b028808559341f85880cc3ba722);
        

        circle_marker_6c1a215101a1dddcde99d4905f2ca7f2.bindPopup(popup_a7dba9eba01acaf0123f1d6bb08dde03)
        ;

        
    
    
            var circle_marker_7ce8a7951827d7ebeb13807b9b0ed18c = L.circleMarker(
                [-3.5, 30.0],
                {"bubblingMouseEvents": true, "color": "green", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "green", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 0.1167680436705472, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_91e6c25103cd31dee77cd70f06aad8b8 = L.popup({"maxWidth": "100%"});

        
            var html_657d3991e23634cd0b1571bbdc70e8d1 = $(`<div id="html_657d3991e23634cd0b1571bbdc70e8d1" style="width: 100.0%; height: 100.0%;">Burundi: 0.0583840218352736 metric tons per capita</div>`)[0];
            popup_91e6c25103cd31dee77cd70f06aad8b8.setContent(html_657d3991e23634cd0b1571bbdc70e8d1);
        

        circle_marker_7ce8a7951827d7ebeb13807b9b0ed18c.bindPopup(popup_91e6c25103cd31dee77cd70f06aad8b8)
        ;

        
    
    
            var circle_marker_6756b433e4269c457583ca6e45ef796c = L.circleMarker(
                [50.8333, 4.0],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "red", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 14.79626131549362, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_c847e493824e9eedc09bf8c8a4295680 = L.popup({"maxWidth": "100%"});

        
            var html_c75c1e2a1d8e927900e3afce6f10c032 = $(`<div id="html_c75c1e2a1d8e927900e3afce6f10c032" style="width: 100.0%; height: 100.0%;">Belgium: 7.39813065774681 metric tons per capita</div>`)[0];
            popup_c847e493824e9eedc09bf8c8a4295680.setContent(html_c75c1e2a1d8e927900e3afce6f10c032);
        

        circle_marker_6756b433e4269c457583ca6e45ef796c.bindPopup(popup_c847e493824e9eedc09bf8c8a4295680)
        ;

        
    
    
            var circle_marker_cfc0cb1d55e4a4ff87aba6fb2ae6ef3e = L.circleMarker(
                [9.5, 2.25],
                {"bubblingMouseEvents": true, "color": "green", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "green", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1.262409611928952, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_0e18688623b16f58ebf96226d826a7f1 = L.popup({"maxWidth": "100%"});

        
            var html_1d898b03df4d4db7fbc1c9fccb09fd2a = $(`<div id="html_1d898b03df4d4db7fbc1c9fccb09fd2a" style="width: 100.0%; height: 100.0%;">Benin: 0.631204805964476 metric tons per capita</div>`)[0];
            popup_0e18688623b16f58ebf96226d826a7f1.setContent(html_1d898b03df4d4db7fbc1c9fccb09fd2a);
        

        circle_marker_cfc0cb1d55e4a4ff87aba6fb2ae6ef3e.bindPopup(popup_0e18688623b16f58ebf96226d826a7f1)
        ;

        
    
    
            var circle_marker_6677edabfd58eab205cc93a5939beb6b = L.circleMarker(
                [13.0, -2.0],
                {"bubblingMouseEvents": true, "color": "green", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "green", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 0.507066377495014, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_45e8a2aee2c5a8021a12342bc538740e = L.popup({"maxWidth": "100%"});

        
            var html_dafe3c6960c44db3f59cf33f4c9f5735 = $(`<div id="html_dafe3c6960c44db3f59cf33f4c9f5735" style="width: 100.0%; height: 100.0%;">Burkina Faso: 0.253533188747507 metric tons per capita</div>`)[0];
            popup_45e8a2aee2c5a8021a12342bc538740e.setContent(html_dafe3c6960c44db3f59cf33f4c9f5735);
        

        circle_marker_6677edabfd58eab205cc93a5939beb6b.bindPopup(popup_45e8a2aee2c5a8021a12342bc538740e)
        ;

        
    
    
            var circle_marker_ba1fa5ebe3413bffc27a203f3cb392d1 = L.circleMarker(
                [24.0, 90.0],
                {"bubblingMouseEvents": true, "color": "green", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "green", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1.021295118554188, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_a8f6a8ad9810fd80835509ab202ac1b9 = L.popup({"maxWidth": "100%"});

        
            var html_ed1301d511b5c423f953489085e66dd5 = $(`<div id="html_ed1301d511b5c423f953489085e66dd5" style="width: 100.0%; height: 100.0%;">Bangladesh: 0.510647559277094 metric tons per capita</div>`)[0];
            popup_a8f6a8ad9810fd80835509ab202ac1b9.setContent(html_ed1301d511b5c423f953489085e66dd5);
        

        circle_marker_ba1fa5ebe3413bffc27a203f3cb392d1.bindPopup(popup_a8f6a8ad9810fd80835509ab202ac1b9)
        ;

        
    
    
            var circle_marker_bc5961192bd48e2971cd97fb29903665 = L.circleMarker(
                [43.0, 25.0],
                {"bubblingMouseEvents": true, "color": "yellow", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "yellow", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 9.84656075881002, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_98b2ab30771d11f38be2435a6818b5ad = L.popup({"maxWidth": "100%"});

        
            var html_2b6b4950c50b78d7578f0bce89c3fcf7 = $(`<div id="html_2b6b4950c50b78d7578f0bce89c3fcf7" style="width: 100.0%; height: 100.0%;">Bulgaria: 4.92328037940501 metric tons per capita</div>`)[0];
            popup_98b2ab30771d11f38be2435a6818b5ad.setContent(html_2b6b4950c50b78d7578f0bce89c3fcf7);
        

        circle_marker_bc5961192bd48e2971cd97fb29903665.bindPopup(popup_98b2ab30771d11f38be2435a6818b5ad)
        ;

        
    
    
            var circle_marker_e2070ede3a075125d1c0c956b370eb10 = L.circleMarker(
                [26.0, 50.55],
                {"bubblingMouseEvents": true, "color": "darkred", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "darkred", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 43.9538156130518, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_d46cd7cd30c2c7a504c5ced625d3b1db = L.popup({"maxWidth": "100%"});

        
            var html_256df6e0ea6170f4ae33b84468b51368 = $(`<div id="html_256df6e0ea6170f4ae33b84468b51368" style="width: 100.0%; height: 100.0%;">Bahrain: 21.9769078065259 metric tons per capita</div>`)[0];
            popup_d46cd7cd30c2c7a504c5ced625d3b1db.setContent(html_256df6e0ea6170f4ae33b84468b51368);
        

        circle_marker_e2070ede3a075125d1c0c956b370eb10.bindPopup(popup_d46cd7cd30c2c7a504c5ced625d3b1db)
        ;

        
    
    
            var circle_marker_31a734c0adcf90f209ff3e8d11dcaa11 = L.circleMarker(
                [24.25, -76.0],
                {"bubblingMouseEvents": true, "color": "orange", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "orange", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 12.08450295347024, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_e8da1fd3f7376e08fdd6a6df6dc6c033 = L.popup({"maxWidth": "100%"});

        
            var html_41d189165cba66a78b71feaf23584796 = $(`<div id="html_41d189165cba66a78b71feaf23584796" style="width: 100.0%; height: 100.0%;">Bahamas: 6.04225147673512 metric tons per capita</div>`)[0];
            popup_e8da1fd3f7376e08fdd6a6df6dc6c033.setContent(html_41d189165cba66a78b71feaf23584796);
        

        circle_marker_31a734c0adcf90f209ff3e8d11dcaa11.bindPopup(popup_e8da1fd3f7376e08fdd6a6df6dc6c033)
        ;

        
    
    
            var circle_marker_c41a7a01e3f19563c8eddfd3b3ea4c51 = L.circleMarker(
                [44.0, 18.0],
                {"bubblingMouseEvents": true, "color": "orange", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "orange", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 12.62461174895062, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_891d85c21dcd84c431522e0c00e4749b = L.popup({"maxWidth": "100%"});

        
            var html_f5031bf8379fcf84eb1a96df74b941cf = $(`<div id="html_f5031bf8379fcf84eb1a96df74b941cf" style="width: 100.0%; height: 100.0%;">Bosnia and Herzegovina: 6.31230587447531 metric tons per capita</div>`)[0];
            popup_891d85c21dcd84c431522e0c00e4749b.setContent(html_f5031bf8379fcf84eb1a96df74b941cf);
        

        circle_marker_c41a7a01e3f19563c8eddfd3b3ea4c51.bindPopup(popup_891d85c21dcd84c431522e0c00e4749b)
        ;

        
    
    
            var circle_marker_fc033925602dd486938fb80307338637 = L.circleMarker(
                [53.0, 28.0],
                {"bubblingMouseEvents": true, "color": "orange", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "orange", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 11.68481459180176, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_d5b3a4b794b7d25bddeb0785101458af = L.popup({"maxWidth": "100%"});

        
            var html_3d54166fae65c1d0bad0d4e73cb7cb6a = $(`<div id="html_3d54166fae65c1d0bad0d4e73cb7cb6a" style="width: 100.0%; height: 100.0%;">Belarus: 5.84240729590088 metric tons per capita</div>`)[0];
            popup_d5b3a4b794b7d25bddeb0785101458af.setContent(html_3d54166fae65c1d0bad0d4e73cb7cb6a);
        

        circle_marker_fc033925602dd486938fb80307338637.bindPopup(popup_d5b3a4b794b7d25bddeb0785101458af)
        ;

        
    
    
            var circle_marker_20f9081d096dfd7637d1160e1eb35740 = L.circleMarker(
                [17.25, -88.75],
                {"bubblingMouseEvents": true, "color": "green", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "green", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3.48221543042786, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_c27fde34e0aae7a037c8795a1c95afee = L.popup({"maxWidth": "100%"});

        
            var html_d911b5af4bd1f4f581905ffc7d70d03c = $(`<div id="html_d911b5af4bd1f4f581905ffc7d70d03c" style="width: 100.0%; height: 100.0%;">Belize: 1.74110771521393 metric tons per capita</div>`)[0];
            popup_c27fde34e0aae7a037c8795a1c95afee.setContent(html_d911b5af4bd1f4f581905ffc7d70d03c);
        

        circle_marker_20f9081d096dfd7637d1160e1eb35740.bindPopup(popup_c27fde34e0aae7a037c8795a1c95afee)
        ;

        
    
    
            var circle_marker_b7f57518276dba87e1adcf086c48c60c = L.circleMarker(
                [-17.0, -65.0],
                {"bubblingMouseEvents": true, "color": "green", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "green", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3.07892939120632, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_d9a06456378547eaff6c2a14370b9a01 = L.popup({"maxWidth": "100%"});

        
            var html_8adfa4498e797756422269e34b161859 = $(`<div id="html_8adfa4498e797756422269e34b161859" style="width: 100.0%; height: 100.0%;">Bolivia: 1.53946469560316 metric tons per capita</div>`)[0];
            popup_d9a06456378547eaff6c2a14370b9a01.setContent(html_8adfa4498e797756422269e34b161859);
        

        circle_marker_b7f57518276dba87e1adcf086c48c60c.bindPopup(popup_d9a06456378547eaff6c2a14370b9a01)
        ;

        
    
    
            var circle_marker_8cc98d75f708b90a764e9336364231a2 = L.circleMarker(
                [-10.0, -55.0],
                {"bubblingMouseEvents": true, "color": "green", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "green", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3.88504671262968, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_0997190e9f1fbb8a7dbbcb2f4d9fa185 = L.popup({"maxWidth": "100%"});

        
            var html_871f80b2ebe74493eed531cb2e1099a7 = $(`<div id="html_871f80b2ebe74493eed531cb2e1099a7" style="width: 100.0%; height: 100.0%;">Brazil: 1.94252335631484 metric tons per capita</div>`)[0];
            popup_0997190e9f1fbb8a7dbbcb2f4d9fa185.setContent(html_871f80b2ebe74493eed531cb2e1099a7);
        

        circle_marker_8cc98d75f708b90a764e9336364231a2.bindPopup(popup_0997190e9f1fbb8a7dbbcb2f4d9fa185)
        ;

        
    
    
            var circle_marker_566d395e289d54598ce204c7447a2ef3 = L.circleMarker(
                [13.1667, -59.5333],
                {"bubblingMouseEvents": true, "color": "yellow", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "yellow", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7.8097423163385, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_a94e52de322309cb800ac8e263516e51 = L.popup({"maxWidth": "100%"});

        
            var html_ef7da5c8848febc84874dca9a9033bd0 = $(`<div id="html_ef7da5c8848febc84874dca9a9033bd0" style="width: 100.0%; height: 100.0%;">Barbados: 3.90487115816925 metric tons per capita</div>`)[0];
            popup_a94e52de322309cb800ac8e263516e51.setContent(html_ef7da5c8848febc84874dca9a9033bd0);
        

        circle_marker_566d395e289d54598ce204c7447a2ef3.bindPopup(popup_a94e52de322309cb800ac8e263516e51)
        ;

        
    
    
            var circle_marker_c2a73b24891a4487297876d386c27b8b = L.circleMarker(
                [4.5, 114.6667],
                {"bubblingMouseEvents": true, "color": "darkred", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "darkred", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 43.4116248797328, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_426db84592c97828fd2cec98e16df4ab = L.popup({"maxWidth": "100%"});

        
            var html_8e6701dacdeead7035dd29f758db4a2e = $(`<div id="html_8e6701dacdeead7035dd29f758db4a2e" style="width: 100.0%; height: 100.0%;">Brunei Darussalam: 21.7058124398664 metric tons per capita</div>`)[0];
            popup_426db84592c97828fd2cec98e16df4ab.setContent(html_8e6701dacdeead7035dd29f758db4a2e);
        

        circle_marker_c2a73b24891a4487297876d386c27b8b.bindPopup(popup_426db84592c97828fd2cec98e16df4ab)
        ;

        
    
    
            var circle_marker_2d4c7408f64babce7cb767fd650aa64c = L.circleMarker(
                [27.5, 90.5],
                {"bubblingMouseEvents": true, "color": "green", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "green", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2.68010863346046, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_f42213e6f297100246b3857156e8572e = L.popup({"maxWidth": "100%"});

        
            var html_93d128ca8e51d7985201bbe09b090e15 = $(`<div id="html_93d128ca8e51d7985201bbe09b090e15" style="width: 100.0%; height: 100.0%;">Bhutan: 1.34005431673023 metric tons per capita</div>`)[0];
            popup_f42213e6f297100246b3857156e8572e.setContent(html_93d128ca8e51d7985201bbe09b090e15);
        

        circle_marker_2d4c7408f64babce7cb767fd650aa64c.bindPopup(popup_f42213e6f297100246b3857156e8572e)
        ;

        
    
    
            var circle_marker_dd2178f9dd54903b5270e567e59230fb = L.circleMarker(
                [-22.0, 24.0],
                {"bubblingMouseEvents": true, "color": "green", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "green", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 4.5269262276734, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_7926b4ea200bee595c1691ce4f35d69d = L.popup({"maxWidth": "100%"});

        
            var html_b8651aa5ae32bcb3e055b3df9527be6e = $(`<div id="html_b8651aa5ae32bcb3e055b3df9527be6e" style="width: 100.0%; height: 100.0%;">Botswana: 2.2634631138367 metric tons per capita</div>`)[0];
            popup_7926b4ea200bee595c1691ce4f35d69d.setContent(html_b8651aa5ae32bcb3e055b3df9527be6e);
        

        circle_marker_dd2178f9dd54903b5270e567e59230fb.bindPopup(popup_7926b4ea200bee595c1691ce4f35d69d)
        ;

        
    
    
            var circle_marker_13c0d46679745c33ab06e1c1a5546bf9 = L.circleMarker(
                [7.0, 21.0],
                {"bubblingMouseEvents": true, "color": "green", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "green", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 0.08856414537097, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_82587fae265e587ffe801a472899c6c3 = L.popup({"maxWidth": "100%"});

        
            var html_899994bb571416d806f02b9b29cbe566 = $(`<div id="html_899994bb571416d806f02b9b29cbe566" style="width: 100.0%; height: 100.0%;">Central African Republic: 0.044282072685485 metric tons per capita</div>`)[0];
            popup_82587fae265e587ffe801a472899c6c3.setContent(html_899994bb571416d806f02b9b29cbe566);
        

        circle_marker_13c0d46679745c33ab06e1c1a5546bf9.bindPopup(popup_82587fae265e587ffe801a472899c6c3)
        ;

        
    
    
            var circle_marker_7d2f00b48dd9f14edf4f50c254231ee6 = L.circleMarker(
                [60.0, -95.0],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "red", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 27.1833926842186, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_a1b09067ffecfd0eaa96bf892824c962 = L.popup({"maxWidth": "100%"});

        
            var html_64c638476657836812fbfb56c77954b7 = $(`<div id="html_64c638476657836812fbfb56c77954b7" style="width: 100.0%; height: 100.0%;">Canada: 13.5916963421093 metric tons per capita</div>`)[0];
            popup_a1b09067ffecfd0eaa96bf892824c962.setContent(html_64c638476657836812fbfb56c77954b7);
        

        circle_marker_7d2f00b48dd9f14edf4f50c254231ee6.bindPopup(popup_a1b09067ffecfd0eaa96bf892824c962)
        ;

        
    
    
            var circle_marker_9ffd972a36af923c707864cebbae7c56 = L.circleMarker(
                [47.0, 8.0],
                {"bubblingMouseEvents": true, "color": "yellow", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "yellow", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8.08414562950682, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_feab8a15908ed73e48d5769993ce3022 = L.popup({"maxWidth": "100%"});

        
            var html_be2518946d54aab1d9267d08b11e56c6 = $(`<div id="html_be2518946d54aab1d9267d08b11e56c6" style="width: 100.0%; height: 100.0%;">Switzerland: 4.04207281475341 metric tons per capita</div>`)[0];
            popup_feab8a15908ed73e48d5769993ce3022.setContent(html_be2518946d54aab1d9267d08b11e56c6);
        

        circle_marker_9ffd972a36af923c707864cebbae7c56.bindPopup(popup_feab8a15908ed73e48d5769993ce3022)
        ;

        
    
    
            var circle_marker_942d60906aab23d38d383eb4e149a404 = L.circleMarker(
                [-30.0, -71.0],
                {"bubblingMouseEvents": true, "color": "yellow", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "yellow", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8.79030212719326, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_0cce0254b46d148da19f5acec977043e = L.popup({"maxWidth": "100%"});

        
            var html_5111948e45c6133512df9e0b06011576 = $(`<div id="html_5111948e45c6133512df9e0b06011576" style="width: 100.0%; height: 100.0%;">Chile: 4.39515106359663 metric tons per capita</div>`)[0];
            popup_0cce0254b46d148da19f5acec977043e.setContent(html_5111948e45c6133512df9e0b06011576);
        

        circle_marker_942d60906aab23d38d383eb4e149a404.bindPopup(popup_0cce0254b46d148da19f5acec977043e)
        ;

        
    
    
            var circle_marker_95a831126ffa60e9d68e9b0602dfb6aa = L.circleMarker(
                [35.0, 105.0],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "red", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 15.51227581319538, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_5bd8dae8705313dcbb7cec93a33613cc = L.popup({"maxWidth": "100%"});

        
            var html_efc135143f3e28af37ce54396fc8ba2d = $(`<div id="html_efc135143f3e28af37ce54396fc8ba2d" style="width: 100.0%; height: 100.0%;">China: 7.75613790659769 metric tons per capita</div>`)[0];
            popup_5bd8dae8705313dcbb7cec93a33613cc.setContent(html_efc135143f3e28af37ce54396fc8ba2d);
        

        circle_marker_95a831126ffa60e9d68e9b0602dfb6aa.bindPopup(popup_5bd8dae8705313dcbb7cec93a33613cc)
        ;

        
    
    
            var circle_marker_c7da44885f239df0caad4020391736ce = L.circleMarker(
                [8.0, -5.0],
                {"bubblingMouseEvents": true, "color": "green", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "green", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 0.812694713780766, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_3095c9e996b6b8ce9986200a9aafc2d6 = L.popup({"maxWidth": "100%"});

        
            var html_b5074cdcf604ffd9a3e9bd5a6db5c58e = $(`<div id="html_b5074cdcf604ffd9a3e9bd5a6db5c58e" style="width: 100.0%; height: 100.0%;">Côte d'Ivoire: 0.406347356890383 metric tons per capita</div>`)[0];
            popup_3095c9e996b6b8ce9986200a9aafc2d6.setContent(html_b5074cdcf604ffd9a3e9bd5a6db5c58e);
        

        circle_marker_c7da44885f239df0caad4020391736ce.bindPopup(popup_3095c9e996b6b8ce9986200a9aafc2d6)
        ;

        
    
    
            var circle_marker_9566a0cc9f6e04320f83587c5f83acf5 = L.circleMarker(
                [6.0, 12.0],
                {"bubblingMouseEvents": true, "color": "green", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "green", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 0.74956531606272, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_f664f3f00240022621d7d369cc360bc2 = L.popup({"maxWidth": "100%"});

        
            var html_75811509bb1225ea95fe560cdfd7fbbd = $(`<div id="html_75811509bb1225ea95fe560cdfd7fbbd" style="width: 100.0%; height: 100.0%;">Cameroon: 0.37478265803136 metric tons per capita</div>`)[0];
            popup_f664f3f00240022621d7d369cc360bc2.setContent(html_75811509bb1225ea95fe560cdfd7fbbd);
        

        circle_marker_9566a0cc9f6e04320f83587c5f83acf5.bindPopup(popup_f664f3f00240022621d7d369cc360bc2)
        ;

        
    
    
            var circle_marker_f03af01f03ac13712370b4e7e47a7f9c = L.circleMarker(
                [0.0, 25.0],
                {"bubblingMouseEvents": true, "color": "green", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "green", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 0.0651695616963574, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_ed30841c74db9681e42f514782ecc9e9 = L.popup({"maxWidth": "100%"});

        
            var html_804f37663f298ce7ee502a421f31fb48 = $(`<div id="html_804f37663f298ce7ee502a421f31fb48" style="width: 100.0%; height: 100.0%;">Congo, the Democratic Republic of the: 0.0325847808481787 metric tons per capita</div>`)[0];
            popup_ed30841c74db9681e42f514782ecc9e9.setContent(html_804f37663f298ce7ee502a421f31fb48);
        

        circle_marker_f03af01f03ac13712370b4e7e47a7f9c.bindPopup(popup_ed30841c74db9681e42f514782ecc9e9)
        ;

        
    
    
            var circle_marker_6e204b89a1a5f47adda0b58062ea3d3e = L.circleMarker(
                [-1.0, 15.0],
                {"bubblingMouseEvents": true, "color": "green", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "green", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2.50918333954734, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_2c54a301f110281c09e8f7303864e9d5 = L.popup({"maxWidth": "100%"});

        
            var html_470636c4efae01d0876462c3bfcc127c = $(`<div id="html_470636c4efae01d0876462c3bfcc127c" style="width: 100.0%; height: 100.0%;">Congo: 1.25459166977367 metric tons per capita</div>`)[0];
            popup_2c54a301f110281c09e8f7303864e9d5.setContent(html_470636c4efae01d0876462c3bfcc127c);
        

        circle_marker_6e204b89a1a5f47adda0b58062ea3d3e.bindPopup(popup_2c54a301f110281c09e8f7303864e9d5)
        ;

        
    
    
            var circle_marker_5eeed474ba4c34066027d85a1b8b4936 = L.circleMarker(
                [4.0, -72.0],
                {"bubblingMouseEvents": true, "color": "green", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "green", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3.10451884564156, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_74416cfb94688f4508d8c27082e3fe58 = L.popup({"maxWidth": "100%"});

        
            var html_037a86fa778e3ba92ccaa6bdfd71e8b3 = $(`<div id="html_037a86fa778e3ba92ccaa6bdfd71e8b3" style="width: 100.0%; height: 100.0%;">Colombia: 1.55225942282078 metric tons per capita</div>`)[0];
            popup_74416cfb94688f4508d8c27082e3fe58.setContent(html_037a86fa778e3ba92ccaa6bdfd71e8b3);
        

        circle_marker_5eeed474ba4c34066027d85a1b8b4936.bindPopup(popup_74416cfb94688f4508d8c27082e3fe58)
        ;

        
    
    
            var circle_marker_a620bce6d735910b75ea8016fcb04044 = L.circleMarker(
                [-12.1667, 44.25],
                {"bubblingMouseEvents": true, "color": "green", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "green", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 0.814224365701356, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_9328e35f61b2ea4eec3a369911d5afbe = L.popup({"maxWidth": "100%"});

        
            var html_69d6556e03c73e88c96d9e6d4ce7c3e8 = $(`<div id="html_69d6556e03c73e88c96d9e6d4ce7c3e8" style="width: 100.0%; height: 100.0%;">Comoros: 0.407112182850678 metric tons per capita</div>`)[0];
            popup_9328e35f61b2ea4eec3a369911d5afbe.setContent(html_69d6556e03c73e88c96d9e6d4ce7c3e8);
        

        circle_marker_a620bce6d735910b75ea8016fcb04044.bindPopup(popup_9328e35f61b2ea4eec3a369911d5afbe)
        ;

        
    
    
            var circle_marker_dd324204e9cc217dea336ae86f655a65 = L.circleMarker(
                [16.0, -24.0],
                {"bubblingMouseEvents": true, "color": "green", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "green", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2.13030344638198, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_ea4040ec44a5afccc4d95c3818c2f356 = L.popup({"maxWidth": "100%"});

        
            var html_6cc7e2f15bdddfd15c3c05274fb3a98e = $(`<div id="html_6cc7e2f15bdddfd15c3c05274fb3a98e" style="width: 100.0%; height: 100.0%;">Cape Verde: 1.06515172319099 metric tons per capita</div>`)[0];
            popup_ea4040ec44a5afccc4d95c3818c2f356.setContent(html_6cc7e2f15bdddfd15c3c05274fb3a98e);
        

        circle_marker_dd324204e9cc217dea336ae86f655a65.bindPopup(popup_ea4040ec44a5afccc4d95c3818c2f356)
        ;

        
    
    
            var circle_marker_ff09efb9c39d15dff5b96b99cd5e353f = L.circleMarker(
                [10.0, -84.0],
                {"bubblingMouseEvents": true, "color": "green", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "green", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2.71999109914788, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_aa7bb1103ec8630db7382f139196db5b = L.popup({"maxWidth": "100%"});

        
            var html_51ff95c448ace8e81878e469d3b82c3e = $(`<div id="html_51ff95c448ace8e81878e469d3b82c3e" style="width: 100.0%; height: 100.0%;">Costa Rica: 1.35999554957394 metric tons per capita</div>`)[0];
            popup_aa7bb1103ec8630db7382f139196db5b.setContent(html_51ff95c448ace8e81878e469d3b82c3e);
        

        circle_marker_ff09efb9c39d15dff5b96b99cd5e353f.bindPopup(popup_aa7bb1103ec8630db7382f139196db5b)
        ;

        
    
    
            var circle_marker_a8c591bfb9c6c33e83c8431d9745976f = L.circleMarker(
                [21.5, -80.0],
                {"bubblingMouseEvents": true, "color": "green", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "green", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 4.30553935694946, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_3df84b266400e6a579e6eeeb55ee1ce2 = L.popup({"maxWidth": "100%"});

        
            var html_d746b10d4ac6234f8342e68e4f86c390 = $(`<div id="html_d746b10d4ac6234f8342e68e4f86c390" style="width: 100.0%; height: 100.0%;">Cuba: 2.15276967847473 metric tons per capita</div>`)[0];
            popup_3df84b266400e6a579e6eeeb55ee1ce2.setContent(html_d746b10d4ac6234f8342e68e4f86c390);
        

        circle_marker_a8c591bfb9c6c33e83c8431d9745976f.bindPopup(popup_3df84b266400e6a579e6eeeb55ee1ce2)
        ;

        
    
    
            var circle_marker_d573901dbe2d6c51860e4e7f925701f2 = L.circleMarker(
                [35.0, 33.0],
                {"bubblingMouseEvents": true, "color": "orange", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "orange", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 10.94399601789684, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_26c1d51b76a146aca2454f4fcca89355 = L.popup({"maxWidth": "100%"});

        
            var html_0b10a5206a4f240ff9889ca1b95f3e87 = $(`<div id="html_0b10a5206a4f240ff9889ca1b95f3e87" style="width: 100.0%; height: 100.0%;">Cyprus: 5.47199800894842 metric tons per capita</div>`)[0];
            popup_26c1d51b76a146aca2454f4fcca89355.setContent(html_0b10a5206a4f240ff9889ca1b95f3e87);
        

        circle_marker_d573901dbe2d6c51860e4e7f925701f2.bindPopup(popup_26c1d51b76a146aca2454f4fcca89355)
        ;

        
    
    
            var circle_marker_3693657aa195c46a5ea23845fd14e457 = L.circleMarker(
                [49.75, 15.5],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "red", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 16.60803499167778, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_570af8ebef96b211fb52667617ccce98 = L.popup({"maxWidth": "100%"});

        
            var html_207b0b275ceec3e527b7426d6b97b4bc = $(`<div id="html_207b0b275ceec3e527b7426d6b97b4bc" style="width: 100.0%; height: 100.0%;">Czech Republic: 8.30401749583889 metric tons per capita</div>`)[0];
            popup_570af8ebef96b211fb52667617ccce98.setContent(html_207b0b275ceec3e527b7426d6b97b4bc);
        

        circle_marker_3693657aa195c46a5ea23845fd14e457.bindPopup(popup_570af8ebef96b211fb52667617ccce98)
        ;

        
    
    
            var circle_marker_9f20a619451f8b09d6c2bdaf8698c639 = L.circleMarker(
                [51.0, 9.0],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "red", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 14.5104420563368, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_5e4bf8e4763a9d168b2ac69c78c98a46 = L.popup({"maxWidth": "100%"});

        
            var html_ab77577372344e018b7f35fa27a6cef7 = $(`<div id="html_ab77577372344e018b7f35fa27a6cef7" style="width: 100.0%; height: 100.0%;">Germany: 7.2552210281684 metric tons per capita</div>`)[0];
            popup_5e4bf8e4763a9d168b2ac69c78c98a46.setContent(html_ab77577372344e018b7f35fa27a6cef7);
        

        circle_marker_9f20a619451f8b09d6c2bdaf8698c639.bindPopup(popup_5e4bf8e4763a9d168b2ac69c78c98a46)
        ;

        
    
    
            var circle_marker_b45029719b141ee899f60d26d407029a = L.circleMarker(
                [11.5, 43.0],
                {"bubblingMouseEvents": true, "color": "green", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "green", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 0.784658342475756, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_6dbbaf01867feca1605fd6f016f02b7f = L.popup({"maxWidth": "100%"});

        
            var html_efc735e152e439046e219cfc2027083f = $(`<div id="html_efc735e152e439046e219cfc2027083f" style="width: 100.0%; height: 100.0%;">Djibouti: 0.392329171237878 metric tons per capita</div>`)[0];
            popup_6dbbaf01867feca1605fd6f016f02b7f.setContent(html_efc735e152e439046e219cfc2027083f);
        

        circle_marker_b45029719b141ee899f60d26d407029a.bindPopup(popup_6dbbaf01867feca1605fd6f016f02b7f)
        ;

        
    
    
            var circle_marker_fb9ab047078b494c6650e4c9aad1dc1d = L.circleMarker(
                [15.4167, -61.3333],
                {"bubblingMouseEvents": true, "color": "green", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "green", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 4.52253628724218, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_473191291a8c64bade0dbad1f421951e = L.popup({"maxWidth": "100%"});

        
            var html_9959c5b52c43210c85ea5b70779ae980 = $(`<div id="html_9959c5b52c43210c85ea5b70779ae980" style="width: 100.0%; height: 100.0%;">Dominica: 2.26126814362109 metric tons per capita</div>`)[0];
            popup_473191291a8c64bade0dbad1f421951e.setContent(html_9959c5b52c43210c85ea5b70779ae980);
        

        circle_marker_fb9ab047078b494c6650e4c9aad1dc1d.bindPopup(popup_473191291a8c64bade0dbad1f421951e)
        ;

        
    
    
            var circle_marker_802e3f85f3b1fcc588dcacd0b75658d9 = L.circleMarker(
                [56.0, 10.0],
                {"bubblingMouseEvents": true, "color": "yellow", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "yellow", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 9.38247461503268, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_daccc80256c012cf3fd0d58aeaf4cdbb = L.popup({"maxWidth": "100%"});

        
            var html_df8f319d796adeb55456a7e906a586d3 = $(`<div id="html_df8f319d796adeb55456a7e906a586d3" style="width: 100.0%; height: 100.0%;">Denmark: 4.69123730751634 metric tons per capita</div>`)[0];
            popup_daccc80256c012cf3fd0d58aeaf4cdbb.setContent(html_df8f319d796adeb55456a7e906a586d3);
        

        circle_marker_802e3f85f3b1fcc588dcacd0b75658d9.bindPopup(popup_daccc80256c012cf3fd0d58aeaf4cdbb)
        ;

        
    
    
            var circle_marker_d743f72e15592d01ac9c8dc8ec12aed7 = L.circleMarker(
                [19.0, -70.6667],
                {"bubblingMouseEvents": true, "color": "green", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "green", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 4.16036344382882, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_fb1600bf24890b2f6e8b82a80e8b6cd6 = L.popup({"maxWidth": "100%"});

        
            var html_a100ec3a1716716d20eac05b05d0c044 = $(`<div id="html_a100ec3a1716716d20eac05b05d0c044" style="width: 100.0%; height: 100.0%;">Dominican Republic: 2.08018172191441 metric tons per capita</div>`)[0];
            popup_fb1600bf24890b2f6e8b82a80e8b6cd6.setContent(html_a100ec3a1716716d20eac05b05d0c044);
        

        circle_marker_d743f72e15592d01ac9c8dc8ec12aed7.bindPopup(popup_fb1600bf24890b2f6e8b82a80e8b6cd6)
        ;

        
    
    
            var circle_marker_24eded1437528d11d5bacb015891d0af = L.circleMarker(
                [28.0, 3.0],
                {"bubblingMouseEvents": true, "color": "yellow", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "yellow", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7.4364467406152, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_c87c9e87230529043308c0b6802b2857 = L.popup({"maxWidth": "100%"});

        
            var html_811eac362a92f7cd71e98c716ab1bedb = $(`<div id="html_811eac362a92f7cd71e98c716ab1bedb" style="width: 100.0%; height: 100.0%;">Algeria: 3.7182233703076 metric tons per capita</div>`)[0];
            popup_c87c9e87230529043308c0b6802b2857.setContent(html_811eac362a92f7cd71e98c716ab1bedb);
        

        circle_marker_24eded1437528d11d5bacb015891d0af.bindPopup(popup_c87c9e87230529043308c0b6802b2857)
        ;

        
    
    
            var circle_marker_d36c07f02e997a9bf97a129a2765a92a = L.circleMarker(
                [-2.0, -77.5],
                {"bubblingMouseEvents": true, "color": "green", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "green", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3.91515069850662, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_127073b525167b470df6f5eb4c074166 = L.popup({"maxWidth": "100%"});

        
            var html_3a13de2f965679128a602b6cdc19eade = $(`<div id="html_3a13de2f965679128a602b6cdc19eade" style="width: 100.0%; height: 100.0%;">Ecuador: 1.95757534925331 metric tons per capita</div>`)[0];
            popup_127073b525167b470df6f5eb4c074166.setContent(html_3a13de2f965679128a602b6cdc19eade);
        

        circle_marker_d36c07f02e997a9bf97a129a2765a92a.bindPopup(popup_127073b525167b470df6f5eb4c074166)
        ;

        
    
    
            var circle_marker_bca2efe6cb58a95ba8a42be26ca0a103 = L.circleMarker(
                [27.0, 30.0],
                {"bubblingMouseEvents": true, "color": "green", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "green", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3.92224514417858, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_1e792e3da0d89f12dae4fc0dcc1f904c = L.popup({"maxWidth": "100%"});

        
            var html_489925b8ba6e89e6ff6a620ee8a0750f = $(`<div id="html_489925b8ba6e89e6ff6a620ee8a0750f" style="width: 100.0%; height: 100.0%;">Egypt: 1.96112257208929 metric tons per capita</div>`)[0];
            popup_1e792e3da0d89f12dae4fc0dcc1f904c.setContent(html_489925b8ba6e89e6ff6a620ee8a0750f);
        

        circle_marker_bca2efe6cb58a95ba8a42be26ca0a103.bindPopup(popup_1e792e3da0d89f12dae4fc0dcc1f904c)
        ;

        
    
    
            var circle_marker_93a71cd3a97ea79c7611eacc597687d9 = L.circleMarker(
                [15.0, 39.0],
                {"bubblingMouseEvents": true, "color": "green", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "green", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 0.397315085936824, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_815a738a9b751e2ea15099c301dddd51 = L.popup({"maxWidth": "100%"});

        
            var html_4b5b716da8e9d2b80059b9457fe21a22 = $(`<div id="html_4b5b716da8e9d2b80059b9457fe21a22" style="width: 100.0%; height: 100.0%;">Eritrea: 0.198657542968412 metric tons per capita</div>`)[0];
            popup_815a738a9b751e2ea15099c301dddd51.setContent(html_4b5b716da8e9d2b80059b9457fe21a22);
        

        circle_marker_93a71cd3a97ea79c7611eacc597687d9.bindPopup(popup_815a738a9b751e2ea15099c301dddd51)
        ;

        
    
    
            var circle_marker_192863bf96958953111a23d998de8e33 = L.circleMarker(
                [40.0, -4.0],
                {"bubblingMouseEvents": true, "color": "yellow", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "yellow", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8.5591891424282, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_79e2ca0d71d0b347cd9ef070da4f3ff2 = L.popup({"maxWidth": "100%"});

        
            var html_a5eb489e79e0488e302133930fc6a47a = $(`<div id="html_a5eb489e79e0488e302133930fc6a47a" style="width: 100.0%; height: 100.0%;">Spain: 4.2795945712141 metric tons per capita</div>`)[0];
            popup_79e2ca0d71d0b347cd9ef070da4f3ff2.setContent(html_a5eb489e79e0488e302133930fc6a47a);
        

        circle_marker_192863bf96958953111a23d998de8e33.bindPopup(popup_79e2ca0d71d0b347cd9ef070da4f3ff2)
        ;

        
    
    
            var circle_marker_691b7656cec171d3667adcb71ef0fb7d = L.circleMarker(
                [59.0, 26.0],
                {"bubblingMouseEvents": true, "color": "orange", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "orange", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 10.67679963174736, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_4111bd9c70c31e73bca7ac8af7e0e8a0 = L.popup({"maxWidth": "100%"});

        
            var html_90bba6541a4c4317eff74556157566dc = $(`<div id="html_90bba6541a4c4317eff74556157566dc" style="width: 100.0%; height: 100.0%;">Estonia: 5.33839981587368 metric tons per capita</div>`)[0];
            popup_4111bd9c70c31e73bca7ac8af7e0e8a0.setContent(html_90bba6541a4c4317eff74556157566dc);
        

        circle_marker_691b7656cec171d3667adcb71ef0fb7d.bindPopup(popup_4111bd9c70c31e73bca7ac8af7e0e8a0)
        ;

        
    
    
            var circle_marker_d7110b258895083e206f6677c40eedd7 = L.circleMarker(
                [8.0, 38.0],
                {"bubblingMouseEvents": true, "color": "green", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "green", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 0.30886354318041, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_90c538b5f088cfd6c36add4d3c1afc1c = L.popup({"maxWidth": "100%"});

        
            var html_eb173a2300f452a4f54f75edfcd828d8 = $(`<div id="html_eb173a2300f452a4f54f75edfcd828d8" style="width: 100.0%; height: 100.0%;">Ethiopia: 0.154431771590205 metric tons per capita</div>`)[0];
            popup_90c538b5f088cfd6c36add4d3c1afc1c.setContent(html_eb173a2300f452a4f54f75edfcd828d8);
        

        circle_marker_d7110b258895083e206f6677c40eedd7.bindPopup(popup_90c538b5f088cfd6c36add4d3c1afc1c)
        ;

        
    
    
            var circle_marker_333fe3ab837599026f96daab58c013ad = L.circleMarker(
                [64.0, 26.0],
                {"bubblingMouseEvents": true, "color": "orange", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "orange", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 13.1402902554515, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_57608e3bfa2e0244157557d1490edad3 = L.popup({"maxWidth": "100%"});

        
            var html_a3d703a8dc9e3ffa143ad2f4263858c3 = $(`<div id="html_a3d703a8dc9e3ffa143ad2f4263858c3" style="width: 100.0%; height: 100.0%;">Finland: 6.57014512772575 metric tons per capita</div>`)[0];
            popup_57608e3bfa2e0244157557d1490edad3.setContent(html_a3d703a8dc9e3ffa143ad2f4263858c3);
        

        circle_marker_333fe3ab837599026f96daab58c013ad.bindPopup(popup_57608e3bfa2e0244157557d1490edad3)
        ;

        
    
    
            var circle_marker_ea01219281c08804f7abd61826c64e47 = L.circleMarker(
                [-18.0, 175.0],
                {"bubblingMouseEvents": true, "color": "green", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "green", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2.23419257688322, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_3f38df3b8b7d8f1b998cff2293c61331 = L.popup({"maxWidth": "100%"});

        
            var html_9899875aa84f4dcc8bb860f44904b592 = $(`<div id="html_9899875aa84f4dcc8bb860f44904b592" style="width: 100.0%; height: 100.0%;">Fiji: 1.11709628844161 metric tons per capita</div>`)[0];
            popup_3f38df3b8b7d8f1b998cff2293c61331.setContent(html_9899875aa84f4dcc8bb860f44904b592);
        

        circle_marker_ea01219281c08804f7abd61826c64e47.bindPopup(popup_3f38df3b8b7d8f1b998cff2293c61331)
        ;

        
    
    
            var circle_marker_7e1c124ea5ec4dbb3a98818a20f34620 = L.circleMarker(
                [46.0, 2.0],
                {"bubblingMouseEvents": true, "color": "yellow", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "yellow", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7.90736490375982, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_b4f21ccbef318469dfbdc83f9170ea7a = L.popup({"maxWidth": "100%"});

        
            var html_e49c64a4d9b9b1a9827d5ddf8615c1d2 = $(`<div id="html_e49c64a4d9b9b1a9827d5ddf8615c1d2" style="width: 100.0%; height: 100.0%;">France: 3.95368245187991 metric tons per capita</div>`)[0];
            popup_b4f21ccbef318469dfbdc83f9170ea7a.setContent(html_e49c64a4d9b9b1a9827d5ddf8615c1d2);
        

        circle_marker_7e1c124ea5ec4dbb3a98818a20f34620.bindPopup(popup_b4f21ccbef318469dfbdc83f9170ea7a)
        ;

        
    
    
            var circle_marker_bfd45e747bd6d6fbfcbdde30981d62b3 = L.circleMarker(
                [6.9167, 158.25],
                {"bubblingMouseEvents": true, "color": "green", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "green", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1.917827770146112, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_20fa751bfdadc43f3ee24e2657ef3b85 = L.popup({"maxWidth": "100%"});

        
            var html_9cf91e2521334c67f0366d8461af31a3 = $(`<div id="html_9cf91e2521334c67f0366d8461af31a3" style="width: 100.0%; height: 100.0%;">Micronesia, Fed. Sts.: 0.958913885073056 metric tons per capita</div>`)[0];
            popup_20fa751bfdadc43f3ee24e2657ef3b85.setContent(html_9cf91e2521334c67f0366d8461af31a3);
        

        circle_marker_bfd45e747bd6d6fbfcbdde30981d62b3.bindPopup(popup_20fa751bfdadc43f3ee24e2657ef3b85)
        ;

        
    
    
            var circle_marker_3ff72e0a420dad84caf82a8cf66fce75 = L.circleMarker(
                [-1.0, 11.75],
                {"bubblingMouseEvents": true, "color": "green", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "green", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 4.66654715029794, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_eac52e25becd5f0f285aa3b3a3d1fde5 = L.popup({"maxWidth": "100%"});

        
            var html_413acce78879465e074b1b51f4cd7e87 = $(`<div id="html_413acce78879465e074b1b51f4cd7e87" style="width: 100.0%; height: 100.0%;">Gabon: 2.33327357514897 metric tons per capita</div>`)[0];
            popup_eac52e25becd5f0f285aa3b3a3d1fde5.setContent(html_413acce78879465e074b1b51f4cd7e87);
        

        circle_marker_3ff72e0a420dad84caf82a8cf66fce75.bindPopup(popup_eac52e25becd5f0f285aa3b3a3d1fde5)
        ;

        
    
    
            var circle_marker_99711c0c3a1d47d72b32cb62378ee182 = L.circleMarker(
                [54.0, -2.0],
                {"bubblingMouseEvents": true, "color": "yellow", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "yellow", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 9.2022845018027, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_5564ad5ae5c87d9f2e7614874f67e737 = L.popup({"maxWidth": "100%"});

        
            var html_83eb8e6574d263032829445ac4d4be39 = $(`<div id="html_83eb8e6574d263032829445ac4d4be39" style="width: 100.0%; height: 100.0%;">United Kingdom: 4.60114225090135 metric tons per capita</div>`)[0];
            popup_5564ad5ae5c87d9f2e7614874f67e737.setContent(html_83eb8e6574d263032829445ac4d4be39);
        

        circle_marker_99711c0c3a1d47d72b32cb62378ee182.bindPopup(popup_5564ad5ae5c87d9f2e7614874f67e737)
        ;

        
    
    
            var circle_marker_5aa9c4b04b61e1a92845dc3051037fdb = L.circleMarker(
                [42.0, 43.5],
                {"bubblingMouseEvents": true, "color": "green", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "green", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 5.50941839237804, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_b10cff0185750a07828fd94310ae8210 = L.popup({"maxWidth": "100%"});

        
            var html_061c886102697ff644b110f2207ddce2 = $(`<div id="html_061c886102697ff644b110f2207ddce2" style="width: 100.0%; height: 100.0%;">Georgia: 2.75470919618902 metric tons per capita</div>`)[0];
            popup_b10cff0185750a07828fd94310ae8210.setContent(html_061c886102697ff644b110f2207ddce2);
        

        circle_marker_5aa9c4b04b61e1a92845dc3051037fdb.bindPopup(popup_b10cff0185750a07828fd94310ae8210)
        ;

        
    
    
            var circle_marker_46d6869b56f78700f939ff38061bc512 = L.circleMarker(
                [8.0, -2.0],
                {"bubblingMouseEvents": true, "color": "green", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "green", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1.20577490628535, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_8d2bac3e445532a466a777a3a28c50be = L.popup({"maxWidth": "100%"});

        
            var html_65c5c842abeac588d981abb440ffbe3e = $(`<div id="html_65c5c842abeac588d981abb440ffbe3e" style="width: 100.0%; height: 100.0%;">Ghana: 0.602887453142675 metric tons per capita</div>`)[0];
            popup_8d2bac3e445532a466a777a3a28c50be.setContent(html_65c5c842abeac588d981abb440ffbe3e);
        

        circle_marker_46d6869b56f78700f939ff38061bc512.bindPopup(popup_8d2bac3e445532a466a777a3a28c50be)
        ;

        
    
    
            var circle_marker_9e52a28d8b01068d32aa333ce96c97e3 = L.circleMarker(
                [11.0, -10.0],
                {"bubblingMouseEvents": true, "color": "green", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "green", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 0.68729230172494, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_e614775673fcaa41e5f2129984392c6d = L.popup({"maxWidth": "100%"});

        
            var html_6e4f924496b9e6d8886beeaddee0b873 = $(`<div id="html_6e4f924496b9e6d8886beeaddee0b873" style="width: 100.0%; height: 100.0%;">Guinea: 0.34364615086247 metric tons per capita</div>`)[0];
            popup_e614775673fcaa41e5f2129984392c6d.setContent(html_6e4f924496b9e6d8886beeaddee0b873);
        

        circle_marker_9e52a28d8b01068d32aa333ce96c97e3.bindPopup(popup_e614775673fcaa41e5f2129984392c6d)
        ;

        
    
    
            var circle_marker_431ea8fa7093b77e94f4809aafee1cb5 = L.circleMarker(
                [13.4667, -16.5667],
                {"bubblingMouseEvents": true, "color": "green", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "green", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 0.47505919786169, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_dc672acd31ba533d51ce4492a99a4735 = L.popup({"maxWidth": "100%"});

        
            var html_b25d510042d1674f5b10e0f92da60286 = $(`<div id="html_b25d510042d1674f5b10e0f92da60286" style="width: 100.0%; height: 100.0%;">Gambia: 0.237529598930845 metric tons per capita</div>`)[0];
            popup_dc672acd31ba533d51ce4492a99a4735.setContent(html_b25d510042d1674f5b10e0f92da60286);
        

        circle_marker_431ea8fa7093b77e94f4809aafee1cb5.bindPopup(popup_dc672acd31ba533d51ce4492a99a4735)
        ;

        
    
    
            var circle_marker_e88194c21aa5a381a90b7f32f50e1096 = L.circleMarker(
                [12.0, -15.0],
                {"bubblingMouseEvents": true, "color": "green", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "green", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 0.326416737935974, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_40cb446028814745c68901c03440037a = L.popup({"maxWidth": "100%"});

        
            var html_a36f708d764b14aab1e315b9633449a5 = $(`<div id="html_a36f708d764b14aab1e315b9633449a5" style="width: 100.0%; height: 100.0%;">Guinea-Bissau: 0.163208368967987 metric tons per capita</div>`)[0];
            popup_40cb446028814745c68901c03440037a.setContent(html_a36f708d764b14aab1e315b9633449a5);
        

        circle_marker_e88194c21aa5a381a90b7f32f50e1096.bindPopup(popup_40cb446028814745c68901c03440037a)
        ;

        
    
    
            var circle_marker_f9220feb1dbe6febae1e04856fb46e0f = L.circleMarker(
                [2.0, 10.0],
                {"bubblingMouseEvents": true, "color": "green", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "green", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 5.45146170324344, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_0ff7ae6eecb8936fceb4ff50f62233d4 = L.popup({"maxWidth": "100%"});

        
            var html_0dcf8f456c22e924ace010f98bee6789 = $(`<div id="html_0dcf8f456c22e924ace010f98bee6789" style="width: 100.0%; height: 100.0%;">Equatorial Guinea: 2.72573085162172 metric tons per capita</div>`)[0];
            popup_0ff7ae6eecb8936fceb4ff50f62233d4.setContent(html_0dcf8f456c22e924ace010f98bee6789);
        

        circle_marker_f9220feb1dbe6febae1e04856fb46e0f.bindPopup(popup_0ff7ae6eecb8936fceb4ff50f62233d4)
        ;

        
    
    
            var circle_marker_85e14b93947dfd561c69f1eec7d5d7da = L.circleMarker(
                [39.0, 22.0],
                {"bubblingMouseEvents": true, "color": "yellow", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "yellow", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 9.53436987403678, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_b6b0881d2f59e7d7bddae731c533288a = L.popup({"maxWidth": "100%"});

        
            var html_0aea7a4534ac91d078b7c78304226604 = $(`<div id="html_0aea7a4534ac91d078b7c78304226604" style="width: 100.0%; height: 100.0%;">Greece: 4.76718493701839 metric tons per capita</div>`)[0];
            popup_b6b0881d2f59e7d7bddae731c533288a.setContent(html_0aea7a4534ac91d078b7c78304226604);
        

        circle_marker_85e14b93947dfd561c69f1eec7d5d7da.bindPopup(popup_b6b0881d2f59e7d7bddae731c533288a)
        ;

        
    
    
            var circle_marker_39e942116ae83badc0631f0431036e5b = L.circleMarker(
                [12.1167, -61.6667],
                {"bubblingMouseEvents": true, "color": "green", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "green", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 5.24813404171014, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_e50ac989e2efb32c578f9df7f8601fdf = L.popup({"maxWidth": "100%"});

        
            var html_459dfd6eff1485ff6ff2aa26b4b50e6a = $(`<div id="html_459dfd6eff1485ff6ff2aa26b4b50e6a" style="width: 100.0%; height: 100.0%;">Grenada: 2.62406702085507 metric tons per capita</div>`)[0];
            popup_e50ac989e2efb32c578f9df7f8601fdf.setContent(html_459dfd6eff1485ff6ff2aa26b4b50e6a);
        

        circle_marker_39e942116ae83badc0631f0431036e5b.bindPopup(popup_e50ac989e2efb32c578f9df7f8601fdf)
        ;

        
    
    
            var circle_marker_e1edfd93f5003c98c431ec07b1393d82 = L.circleMarker(
                [15.5, -90.25],
                {"bubblingMouseEvents": true, "color": "green", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "green", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2.00081467129638, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_92d1276570e9d6f0e2d6aa48f08376e7 = L.popup({"maxWidth": "100%"});

        
            var html_2b24f173af1390465a1ef8c62b4059de = $(`<div id="html_2b24f173af1390465a1ef8c62b4059de" style="width: 100.0%; height: 100.0%;">Guatemala: 1.00040733564819 metric tons per capita</div>`)[0];
            popup_92d1276570e9d6f0e2d6aa48f08376e7.setContent(html_2b24f173af1390465a1ef8c62b4059de);
        

        circle_marker_e1edfd93f5003c98c431ec07b1393d82.bindPopup(popup_92d1276570e9d6f0e2d6aa48f08376e7)
        ;

        
    
    
            var circle_marker_c6ec6c71273c5aa0168c85dad4458ac9 = L.circleMarker(
                [5.0, -59.0],
                {"bubblingMouseEvents": true, "color": "yellow", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "yellow", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 6.94554203326134, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_7d92c3f84a76ac033fb024b2d7f3256d = L.popup({"maxWidth": "100%"});

        
            var html_841c315b3200c4aef8ca5a47daaafb40 = $(`<div id="html_841c315b3200c4aef8ca5a47daaafb40" style="width: 100.0%; height: 100.0%;">Guyana: 3.47277101663067 metric tons per capita</div>`)[0];
            popup_7d92c3f84a76ac033fb024b2d7f3256d.setContent(html_841c315b3200c4aef8ca5a47daaafb40);
        

        circle_marker_c6ec6c71273c5aa0168c85dad4458ac9.bindPopup(popup_7d92c3f84a76ac033fb024b2d7f3256d)
        ;

        
    
    
            var circle_marker_0f187287edab8aad86739f0a19d8cebd = L.circleMarker(
                [15.0, -86.5],
                {"bubblingMouseEvents": true, "color": "green", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "green", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1.745822343400058, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_eb1c29a5b0bc2a489302fc98fed8088c = L.popup({"maxWidth": "100%"});

        
            var html_dac44899b984602794535ecb088c4511 = $(`<div id="html_dac44899b984602794535ecb088c4511" style="width: 100.0%; height: 100.0%;">Honduras: 0.872911171700029 metric tons per capita</div>`)[0];
            popup_eb1c29a5b0bc2a489302fc98fed8088c.setContent(html_dac44899b984602794535ecb088c4511);
        

        circle_marker_0f187287edab8aad86739f0a19d8cebd.bindPopup(popup_eb1c29a5b0bc2a489302fc98fed8088c)
        ;

        
    
    
            var circle_marker_b196136150efd9f1f94d17b51dd177e6 = L.circleMarker(
                [45.1667, 15.5],
                {"bubblingMouseEvents": true, "color": "yellow", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "yellow", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7.72141078346114, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_54ab257559e32d67458161e981d228ed = L.popup({"maxWidth": "100%"});

        
            var html_ff19f5c7da6100feee0cfce1a42a928d = $(`<div id="html_ff19f5c7da6100feee0cfce1a42a928d" style="width: 100.0%; height: 100.0%;">Croatia: 3.86070539173057 metric tons per capita</div>`)[0];
            popup_54ab257559e32d67458161e981d228ed.setContent(html_ff19f5c7da6100feee0cfce1a42a928d);
        

        circle_marker_b196136150efd9f1f94d17b51dd177e6.bindPopup(popup_54ab257559e32d67458161e981d228ed)
        ;

        
    
    
            var circle_marker_e82aa027405955bd8a24407c44aa401e = L.circleMarker(
                [19.0, -72.4167],
                {"bubblingMouseEvents": true, "color": "green", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "green", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 0.567630048499128, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_5607adb2392a20ab1013b72bb4a2ce00 = L.popup({"maxWidth": "100%"});

        
            var html_fd93be65cd90d4a85cd7a695a7ba4639 = $(`<div id="html_fd93be65cd90d4a85cd7a695a7ba4639" style="width: 100.0%; height: 100.0%;">Haiti: 0.283815024249564 metric tons per capita</div>`)[0];
            popup_5607adb2392a20ab1013b72bb4a2ce00.setContent(html_fd93be65cd90d4a85cd7a695a7ba4639);
        

        circle_marker_e82aa027405955bd8a24407c44aa401e.bindPopup(popup_5607adb2392a20ab1013b72bb4a2ce00)
        ;

        
    
    
            var circle_marker_22896208b05fd33f5e692d10941032f8 = L.circleMarker(
                [47.0, 20.0],
                {"bubblingMouseEvents": true, "color": "yellow", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "yellow", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 9.18330581409576, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_37e71aa7167ed83adea7fb83ffed7711 = L.popup({"maxWidth": "100%"});

        
            var html_c04a9f4cc7c2b0b3e5fc1f1c401f89f3 = $(`<div id="html_c04a9f4cc7c2b0b3e5fc1f1c401f89f3" style="width: 100.0%; height: 100.0%;">Hungary: 4.59165290704788 metric tons per capita</div>`)[0];
            popup_37e71aa7167ed83adea7fb83ffed7711.setContent(html_c04a9f4cc7c2b0b3e5fc1f1c401f89f3);
        

        circle_marker_22896208b05fd33f5e692d10941032f8.bindPopup(popup_37e71aa7167ed83adea7fb83ffed7711)
        ;

        
    
    
            var circle_marker_1d5ee640fb8706dcb65f6f24bc14ce77 = L.circleMarker(
                [-5.0, 120.0],
                {"bubblingMouseEvents": true, "color": "green", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "green", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 4.14331792442944, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_4202ab0056f5bc9a47d9ae0ad9dc5437 = L.popup({"maxWidth": "100%"});

        
            var html_5a584fe14e3ebbc1e2da57c9e2c9d333 = $(`<div id="html_5a584fe14e3ebbc1e2da57c9e2c9d333" style="width: 100.0%; height: 100.0%;">Indonesia: 2.07165896221472 metric tons per capita</div>`)[0];
            popup_4202ab0056f5bc9a47d9ae0ad9dc5437.setContent(html_5a584fe14e3ebbc1e2da57c9e2c9d333);
        

        circle_marker_1d5ee640fb8706dcb65f6f24bc14ce77.bindPopup(popup_4202ab0056f5bc9a47d9ae0ad9dc5437)
        ;

        
    
    
            var circle_marker_5c71fafb73be8e351cdc33b7d71ffb70 = L.circleMarker(
                [20.0, 77.0],
                {"bubblingMouseEvents": true, "color": "green", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "green", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3.15218646383296, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_a3f665cbab0789a72de57c64f946fefc = L.popup({"maxWidth": "100%"});

        
            var html_6a948d6263c6d445aaca8ac5b1c284d7 = $(`<div id="html_6a948d6263c6d445aaca8ac5b1c284d7" style="width: 100.0%; height: 100.0%;">India: 1.57609323191648 metric tons per capita</div>`)[0];
            popup_a3f665cbab0789a72de57c64f946fefc.setContent(html_6a948d6263c6d445aaca8ac5b1c284d7);
        

        circle_marker_5c71fafb73be8e351cdc33b7d71ffb70.bindPopup(popup_a3f665cbab0789a72de57c64f946fefc)
        ;

        
    
    
            var circle_marker_a10edec84b55128ab3367fdfbc181c0e = L.circleMarker(
                [53.0, -8.0],
                {"bubblingMouseEvents": true, "color": "orange", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "orange", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 13.53645518036532, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_1970474842e1d2885b4aa47a77a87209 = L.popup({"maxWidth": "100%"});

        
            var html_f2e14e06e80cd377c659e7840296eb33 = $(`<div id="html_f2e14e06e80cd377c659e7840296eb33" style="width: 100.0%; height: 100.0%;">Ireland: 6.76822759018266 metric tons per capita</div>`)[0];
            popup_1970474842e1d2885b4aa47a77a87209.setContent(html_f2e14e06e80cd377c659e7840296eb33);
        

        circle_marker_a10edec84b55128ab3367fdfbc181c0e.bindPopup(popup_1970474842e1d2885b4aa47a77a87209)
        ;

        
    
    
            var circle_marker_2688d9dab8907382c4279c1452966b2e = L.circleMarker(
                [32.0, 53.0],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "red", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 14.12670264115466, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_7617e24ab788e138ea975ee61811ac68 = L.popup({"maxWidth": "100%"});

        
            var html_56bd891a60d92e718a9c40413f0369bf = $(`<div id="html_56bd891a60d92e718a9c40413f0369bf" style="width: 100.0%; height: 100.0%;">Iran, Islamic Republic of: 7.06335132057733 metric tons per capita</div>`)[0];
            popup_7617e24ab788e138ea975ee61811ac68.setContent(html_56bd891a60d92e718a9c40413f0369bf);
        

        circle_marker_2688d9dab8907382c4279c1452966b2e.bindPopup(popup_7617e24ab788e138ea975ee61811ac68)
        ;

        
    
    
            var circle_marker_86146dd6188ffaffbb6bd368b0d78b6a = L.circleMarker(
                [33.0, 44.0],
                {"bubblingMouseEvents": true, "color": "yellow", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "yellow", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7.68435563948798, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_3e31cef8ba2cf9aff432bd79598bc9ef = L.popup({"maxWidth": "100%"});

        
            var html_3e755e8caa2919e7173eea505990ef0f = $(`<div id="html_3e755e8caa2919e7173eea505990ef0f" style="width: 100.0%; height: 100.0%;">Iraq: 3.84217781974399 metric tons per capita</div>`)[0];
            popup_3e31cef8ba2cf9aff432bd79598bc9ef.setContent(html_3e755e8caa2919e7173eea505990ef0f);
        

        circle_marker_86146dd6188ffaffbb6bd368b0d78b6a.bindPopup(popup_3e31cef8ba2cf9aff432bd79598bc9ef)
        ;

        
    
    
            var circle_marker_8f985a230295c3663b3a10d35cdaec7f = L.circleMarker(
                [65.0, -18.0],
                {"bubblingMouseEvents": true, "color": "yellow", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "yellow", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7.89493072970532, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_8064cef75606f0f36415a1aba00a5640 = L.popup({"maxWidth": "100%"});

        
            var html_1f8015c8d5c6fe03e47d77372d6e6ecf = $(`<div id="html_1f8015c8d5c6fe03e47d77372d6e6ecf" style="width: 100.0%; height: 100.0%;">Iceland: 3.94746536485266 metric tons per capita</div>`)[0];
            popup_8064cef75606f0f36415a1aba00a5640.setContent(html_1f8015c8d5c6fe03e47d77372d6e6ecf);
        

        circle_marker_8f985a230295c3663b3a10d35cdaec7f.bindPopup(popup_8064cef75606f0f36415a1aba00a5640)
        ;

        
    
    
            var circle_marker_2f591632fee89d37105ff5d262b46379 = L.circleMarker(
                [31.5, 34.75],
                {"bubblingMouseEvents": true, "color": "orange", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "orange", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 12.69043200833414, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_c2c847442075b6972abd3507b8e982ea = L.popup({"maxWidth": "100%"});

        
            var html_3e45ac783065ec88e5407cc6ad6b7f0a = $(`<div id="html_3e45ac783065ec88e5407cc6ad6b7f0a" style="width: 100.0%; height: 100.0%;">Israel: 6.34521600416707 metric tons per capita</div>`)[0];
            popup_c2c847442075b6972abd3507b8e982ea.setContent(html_3e45ac783065ec88e5407cc6ad6b7f0a);
        

        circle_marker_2f591632fee89d37105ff5d262b46379.bindPopup(popup_c2c847442075b6972abd3507b8e982ea)
        ;

        
    
    
            var circle_marker_3acf9217e165774715d0c93c2c81b0fd = L.circleMarker(
                [42.8333, 12.8333],
                {"bubblingMouseEvents": true, "color": "yellow", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "yellow", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 9.4647455415987, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_b191e454edbca363785b63014da240fa = L.popup({"maxWidth": "100%"});

        
            var html_a253ce80757bf8130d5a2abb20089784 = $(`<div id="html_a253ce80757bf8130d5a2abb20089784" style="width: 100.0%; height: 100.0%;">Italy: 4.73237277079935 metric tons per capita</div>`)[0];
            popup_b191e454edbca363785b63014da240fa.setContent(html_a253ce80757bf8130d5a2abb20089784);
        

        circle_marker_3acf9217e165774715d0c93c2c81b0fd.bindPopup(popup_b191e454edbca363785b63014da240fa)
        ;

        
    
    
            var circle_marker_1f5da8dc85d71e0356ec828125c7592b = L.circleMarker(
                [18.25, -77.5],
                {"bubblingMouseEvents": true, "color": "green", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "green", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 4.13808361544102, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_f1852101b14d70fcc966afd3537a1085 = L.popup({"maxWidth": "100%"});

        
            var html_deb72932eca81093da8bc7a69fa3ab6c = $(`<div id="html_deb72932eca81093da8bc7a69fa3ab6c" style="width: 100.0%; height: 100.0%;">Jamaica: 2.06904180772051 metric tons per capita</div>`)[0];
            popup_f1852101b14d70fcc966afd3537a1085.setContent(html_deb72932eca81093da8bc7a69fa3ab6c);
        

        circle_marker_1f5da8dc85d71e0356ec828125c7592b.bindPopup(popup_f1852101b14d70fcc966afd3537a1085)
        ;

        
    
    
            var circle_marker_7f26145795056e96107dcac87008eb35 = L.circleMarker(
                [31.0, 36.0],
                {"bubblingMouseEvents": true, "color": "green", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "green", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3.8383448529796, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_e155a5b143f1dc63730caad83bfa185e = L.popup({"maxWidth": "100%"});

        
            var html_d347bc8a36cf23a51f2e62021ddd33fd = $(`<div id="html_d347bc8a36cf23a51f2e62021ddd33fd" style="width: 100.0%; height: 100.0%;">Jordan: 1.9191724264898 metric tons per capita</div>`)[0];
            popup_e155a5b143f1dc63730caad83bfa185e.setContent(html_d347bc8a36cf23a51f2e62021ddd33fd);
        

        circle_marker_7f26145795056e96107dcac87008eb35.bindPopup(popup_e155a5b143f1dc63730caad83bfa185e)
        ;

        
    
    
            var circle_marker_930c163eb76732cc365b0bafbb15f91c = L.circleMarker(
                [36.0, 138.0],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "red", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 16.0629917393336, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_b9d8d534443f7c8c68d17f7cb899534a = L.popup({"maxWidth": "100%"});

        
            var html_7a2d47e57512a50e37383fd8bd18bdff = $(`<div id="html_7a2d47e57512a50e37383fd8bd18bdff" style="width: 100.0%; height: 100.0%;">Japan: 8.0314958696668 metric tons per capita</div>`)[0];
            popup_b9d8d534443f7c8c68d17f7cb899534a.setContent(html_7a2d47e57512a50e37383fd8bd18bdff);
        

        circle_marker_930c163eb76732cc365b0bafbb15f91c.bindPopup(popup_b9d8d534443f7c8c68d17f7cb899534a)
        ;

        
    
    
            var circle_marker_355fc01ac5a837a482176345e1d38061 = L.circleMarker(
                [48.0, 68.0],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "red", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 22.5954866118858, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_71e684af24f907307a4f12b41db3c09c = L.popup({"maxWidth": "100%"});

        
            var html_99cfccbba3dabcaccc0793790f8df390 = $(`<div id="html_99cfccbba3dabcaccc0793790f8df390" style="width: 100.0%; height: 100.0%;">Kazakhstan: 11.2977433059429 metric tons per capita</div>`)[0];
            popup_71e684af24f907307a4f12b41db3c09c.setContent(html_99cfccbba3dabcaccc0793790f8df390);
        

        circle_marker_355fc01ac5a837a482176345e1d38061.bindPopup(popup_71e684af24f907307a4f12b41db3c09c)
        ;

        
    
    
            var circle_marker_61de9208d8d4e70ab757d579ee2b8d1e = L.circleMarker(
                [1.0, 38.0],
                {"bubblingMouseEvents": true, "color": "green", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "green", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 0.74815843871151, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_0a8f80360554762a3056d630806f3cb2 = L.popup({"maxWidth": "100%"});

        
            var html_4eb5efdb1cca93da90d60e8ced05bd7e = $(`<div id="html_4eb5efdb1cca93da90d60e8ced05bd7e" style="width: 100.0%; height: 100.0%;">Kenya: 0.374079219355755 metric tons per capita</div>`)[0];
            popup_0a8f80360554762a3056d630806f3cb2.setContent(html_4eb5efdb1cca93da90d60e8ced05bd7e);
        

        circle_marker_61de9208d8d4e70ab757d579ee2b8d1e.bindPopup(popup_0a8f80360554762a3056d630806f3cb2)
        ;

        
    
    
            var circle_marker_1b9229ae0a3e8426a9ef0866c36298ea = L.circleMarker(
                [41.0, 75.0],
                {"bubblingMouseEvents": true, "color": "green", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "green", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2.75995075913008, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_56bb788168d34956985f869390dcdf71 = L.popup({"maxWidth": "100%"});

        
            var html_43bec11fb93c5f209f61beab1b2d176f = $(`<div id="html_43bec11fb93c5f209f61beab1b2d176f" style="width: 100.0%; height: 100.0%;">Kyrgyzstan: 1.37997537956504 metric tons per capita</div>`)[0];
            popup_56bb788168d34956985f869390dcdf71.setContent(html_43bec11fb93c5f209f61beab1b2d176f);
        

        circle_marker_1b9229ae0a3e8426a9ef0866c36298ea.bindPopup(popup_56bb788168d34956985f869390dcdf71)
        ;

        
    
    
            var circle_marker_4ec0cce908fe84bc686a7492143cc8af = L.circleMarker(
                [13.0, 105.0],
                {"bubblingMouseEvents": true, "color": "green", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "green", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2.27516731862076, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_3fc422ab604bf223c1d94424d9f87e8a = L.popup({"maxWidth": "100%"});

        
            var html_72b87a3df2957dff3896055c0df18786 = $(`<div id="html_72b87a3df2957dff3896055c0df18786" style="width: 100.0%; height: 100.0%;">Cambodia: 1.13758365931038 metric tons per capita</div>`)[0];
            popup_3fc422ab604bf223c1d94424d9f87e8a.setContent(html_72b87a3df2957dff3896055c0df18786);
        

        circle_marker_4ec0cce908fe84bc686a7492143cc8af.bindPopup(popup_3fc422ab604bf223c1d94424d9f87e8a)
        ;

        
    
    
            var circle_marker_5d90b9d994b51f110043a8b01dde33af = L.circleMarker(
                [1.4167, 173.0],
                {"bubblingMouseEvents": true, "color": "green", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "green", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 0.899867945565106, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_6d559656fd10da7d9d18009d52abd247 = L.popup({"maxWidth": "100%"});

        
            var html_dae7be58e88295a186b7687019e3ede8 = $(`<div id="html_dae7be58e88295a186b7687019e3ede8" style="width: 100.0%; height: 100.0%;">Kiribati: 0.449933972782553 metric tons per capita</div>`)[0];
            popup_6d559656fd10da7d9d18009d52abd247.setContent(html_dae7be58e88295a186b7687019e3ede8);
        

        circle_marker_5d90b9d994b51f110043a8b01dde33af.bindPopup(popup_6d559656fd10da7d9d18009d52abd247)
        ;

        
    
    
            var circle_marker_fb1a14532f75edd823f4d842edd8c3b4 = L.circleMarker(
                [17.3333, -62.75],
                {"bubblingMouseEvents": true, "color": "yellow", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "yellow", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 9.69732588892154, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_8cdc189c301a4ff1540406d5d16d313f = L.popup({"maxWidth": "100%"});

        
            var html_a24a2fd3027fe01b756185e9ca411303 = $(`<div id="html_a24a2fd3027fe01b756185e9ca411303" style="width: 100.0%; height: 100.0%;">St. Kitts and Nevis: 4.84866294446077 metric tons per capita</div>`)[0];
            popup_8cdc189c301a4ff1540406d5d16d313f.setContent(html_a24a2fd3027fe01b756185e9ca411303);
        

        circle_marker_fb1a14532f75edd823f4d842edd8c3b4.bindPopup(popup_8cdc189c301a4ff1540406d5d16d313f)
        ;

        
    
    
            var circle_marker_3f4b741b28117d201c3aa7e22a0ab84d = L.circleMarker(
                [37.0, 127.5],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "red", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 21.980059162857, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_51ba0945423528e39165c96a66adf8b7 = L.popup({"maxWidth": "100%"});

        
            var html_195670ace9130a944b90061ecbe16c78 = $(`<div id="html_195670ace9130a944b90061ecbe16c78" style="width: 100.0%; height: 100.0%;">Korea, Republic of: 10.9900295814285 metric tons per capita</div>`)[0];
            popup_51ba0945423528e39165c96a66adf8b7.setContent(html_195670ace9130a944b90061ecbe16c78);
        

        circle_marker_3f4b741b28117d201c3aa7e22a0ab84d.bindPopup(popup_51ba0945423528e39165c96a66adf8b7)
        ;

        
    
    
            var circle_marker_0c7a5dc63f4c79bc44160574df4b2bd5 = L.circleMarker(
                [29.3375, 47.6581],
                {"bubblingMouseEvents": true, "color": "darkred", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "darkred", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 42.3392205013984, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_299e99fac06f05b3d8adb892ed01687d = L.popup({"maxWidth": "100%"});

        
            var html_eac6a60e11cd1f243c50ad98141efe51 = $(`<div id="html_eac6a60e11cd1f243c50ad98141efe51" style="width: 100.0%; height: 100.0%;">Kuwait: 21.1696102506992 metric tons per capita</div>`)[0];
            popup_299e99fac06f05b3d8adb892ed01687d.setContent(html_eac6a60e11cd1f243c50ad98141efe51);
        

        circle_marker_0c7a5dc63f4c79bc44160574df4b2bd5.bindPopup(popup_299e99fac06f05b3d8adb892ed01687d)
        ;

        
    
    
            var circle_marker_feac0ea731fb25c6b9781d1bc2ed5a15 = L.circleMarker(
                [18.0, 105.0],
                {"bubblingMouseEvents": true, "color": "green", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "green", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 5.2405668826088, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_2a35ce3afe49f7405b789fc66355c3fa = L.popup({"maxWidth": "100%"});

        
            var html_feeba04c7a0d466e959c53554db6dae9 = $(`<div id="html_feeba04c7a0d466e959c53554db6dae9" style="width: 100.0%; height: 100.0%;">Lao People's Democratic Republic: 2.6202834413044 metric tons per capita</div>`)[0];
            popup_2a35ce3afe49f7405b789fc66355c3fa.setContent(html_feeba04c7a0d466e959c53554db6dae9);
        

        circle_marker_feac0ea731fb25c6b9781d1bc2ed5a15.bindPopup(popup_2a35ce3afe49f7405b789fc66355c3fa)
        ;

        
    
    
            var circle_marker_3a349d04170a9ce333724415ef983890 = L.circleMarker(
                [33.8333, 35.8333],
                {"bubblingMouseEvents": true, "color": "yellow", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "yellow", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7.58438707360138, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_e2e84164ca1a820574d8b43751f4a794 = L.popup({"maxWidth": "100%"});

        
            var html_4b6dc6dccec490e66660a337aacc1f49 = $(`<div id="html_4b6dc6dccec490e66660a337aacc1f49" style="width: 100.0%; height: 100.0%;">Lebanon: 3.79219353680069 metric tons per capita</div>`)[0];
            popup_e2e84164ca1a820574d8b43751f4a794.setContent(html_4b6dc6dccec490e66660a337aacc1f49);
        

        circle_marker_3a349d04170a9ce333724415ef983890.bindPopup(popup_e2e84164ca1a820574d8b43751f4a794)
        ;

        
    
    
            var circle_marker_093d07e13522ff96a1db02cbfe502062 = L.circleMarker(
                [6.5, -9.5],
                {"bubblingMouseEvents": true, "color": "green", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "green", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 0.463677847874354, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_a066d6e4ae2cf2a9a7a5a815c5dcf869 = L.popup({"maxWidth": "100%"});

        
            var html_4995c0c1c8a8a38ac2b9b7632d008042 = $(`<div id="html_4995c0c1c8a8a38ac2b9b7632d008042" style="width: 100.0%; height: 100.0%;">Liberia: 0.231838923937177 metric tons per capita</div>`)[0];
            popup_a066d6e4ae2cf2a9a7a5a815c5dcf869.setContent(html_4995c0c1c8a8a38ac2b9b7632d008042);
        

        circle_marker_093d07e13522ff96a1db02cbfe502062.bindPopup(popup_a066d6e4ae2cf2a9a7a5a815c5dcf869)
        ;

        
    
    
            var circle_marker_36915b3058683924dfe91fdab10a3d64 = L.circleMarker(
                [25.0, 17.0],
                {"bubblingMouseEvents": true, "color": "orange", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "orange", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 13.36561094160424, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_dbc33c75021e92515ba55f9b4cff00d1 = L.popup({"maxWidth": "100%"});

        
            var html_1f5fc54e9ffcdffee46c6807daee4d55 = $(`<div id="html_1f5fc54e9ffcdffee46c6807daee4d55" style="width: 100.0%; height: 100.0%;">Libya: 6.68280547080212 metric tons per capita</div>`)[0];
            popup_dbc33c75021e92515ba55f9b4cff00d1.setContent(html_1f5fc54e9ffcdffee46c6807daee4d55);
        

        circle_marker_36915b3058683924dfe91fdab10a3d64.bindPopup(popup_dbc33c75021e92515ba55f9b4cff00d1)
        ;

        
    
    
            var circle_marker_f73d183a5b8d1b55e46635c91ccc3884 = L.circleMarker(
                [13.8833, -61.1333],
                {"bubblingMouseEvents": true, "color": "green", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "green", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 5.57027845813086, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_57956a0aa806e3af71b546ee2279dfa7 = L.popup({"maxWidth": "100%"});

        
            var html_35a3e55edeab9163373d7aa1911591cb = $(`<div id="html_35a3e55edeab9163373d7aa1911591cb" style="width: 100.0%; height: 100.0%;">St. Lucia: 2.78513922906543 metric tons per capita</div>`)[0];
            popup_57956a0aa806e3af71b546ee2279dfa7.setContent(html_35a3e55edeab9163373d7aa1911591cb);
        

        circle_marker_f73d183a5b8d1b55e46635c91ccc3884.bindPopup(popup_57956a0aa806e3af71b546ee2279dfa7)
        ;

        
    
    
            var circle_marker_0b293c2227bb1990c7866f42f4a9d999 = L.circleMarker(
                [47.1667, 9.5333],
                {"bubblingMouseEvents": true, "color": "yellow", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "yellow", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7.32769599545876, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_00260e95eea4329cf7069243de41eff7 = L.popup({"maxWidth": "100%"});

        
            var html_45f0512b26909c6d636202993308816e = $(`<div id="html_45f0512b26909c6d636202993308816e" style="width: 100.0%; height: 100.0%;">Liechtenstein: 3.66384799772938 metric tons per capita</div>`)[0];
            popup_00260e95eea4329cf7069243de41eff7.setContent(html_45f0512b26909c6d636202993308816e);
        

        circle_marker_0b293c2227bb1990c7866f42f4a9d999.bindPopup(popup_00260e95eea4329cf7069243de41eff7)
        ;

        
    
    
            var circle_marker_3fe310cd6e6ac01e5eff304e0e8a983e = L.circleMarker(
                [7.0, 81.0],
                {"bubblingMouseEvents": true, "color": "green", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "green", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1.99336648569734, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_18fbfe4298c4df1de721509102059083 = L.popup({"maxWidth": "100%"});

        
            var html_219523b1960c2a64ca8d717003763328 = $(`<div id="html_219523b1960c2a64ca8d717003763328" style="width: 100.0%; height: 100.0%;">Sri Lanka: 0.99668324284867 metric tons per capita</div>`)[0];
            popup_18fbfe4298c4df1de721509102059083.setContent(html_219523b1960c2a64ca8d717003763328);
        

        circle_marker_3fe310cd6e6ac01e5eff304e0e8a983e.bindPopup(popup_18fbfe4298c4df1de721509102059083)
        ;

        
    
    
            var circle_marker_65eb3632bd919a95fbdc3e451a2cc371 = L.circleMarker(
                [-29.5, 28.5],
                {"bubblingMouseEvents": true, "color": "green", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "green", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2.05128432633868, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_4253eab88a7a1a82302da7cc331f17a0 = L.popup({"maxWidth": "100%"});

        
            var html_72b545a1a7fd25766b99a929dc8f47ae = $(`<div id="html_72b545a1a7fd25766b99a929dc8f47ae" style="width: 100.0%; height: 100.0%;">Lesotho: 1.02564216316934 metric tons per capita</div>`)[0];
            popup_4253eab88a7a1a82302da7cc331f17a0.setContent(html_72b545a1a7fd25766b99a929dc8f47ae);
        

        circle_marker_65eb3632bd919a95fbdc3e451a2cc371.bindPopup(popup_4253eab88a7a1a82302da7cc331f17a0)
        ;

        
    
    
            var circle_marker_06dd956fb16db7105eb5ad6064674360 = L.circleMarker(
                [56.0, 24.0],
                {"bubblingMouseEvents": true, "color": "yellow", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "yellow", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8.36800083008782, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_d28064fffe05d1f8e43e8fb0a43f150f = L.popup({"maxWidth": "100%"});

        
            var html_3804cad0f6bad6cfd7fc4e38acdd328e = $(`<div id="html_3804cad0f6bad6cfd7fc4e38acdd328e" style="width: 100.0%; height: 100.0%;">Lithuania: 4.18400041504391 metric tons per capita</div>`)[0];
            popup_d28064fffe05d1f8e43e8fb0a43f150f.setContent(html_3804cad0f6bad6cfd7fc4e38acdd328e);
        

        circle_marker_06dd956fb16db7105eb5ad6064674360.bindPopup(popup_d28064fffe05d1f8e43e8fb0a43f150f)
        ;

        
    
    
            var circle_marker_d3935e226d299b54ebfe327da67b02c4 = L.circleMarker(
                [49.75, 6.1667],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "red", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 24.9139064653826, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_cf5af14f7b34f54629e7454c49a7c824 = L.popup({"maxWidth": "100%"});

        
            var html_0668a50ee9b5e7a742c309054979f4bb = $(`<div id="html_0668a50ee9b5e7a742c309054979f4bb" style="width: 100.0%; height: 100.0%;">Luxembourg: 12.4569532326913 metric tons per capita</div>`)[0];
            popup_cf5af14f7b34f54629e7454c49a7c824.setContent(html_0668a50ee9b5e7a742c309054979f4bb);
        

        circle_marker_d3935e226d299b54ebfe327da67b02c4.bindPopup(popup_cf5af14f7b34f54629e7454c49a7c824)
        ;

        
    
    
            var circle_marker_032c48d911e53ca096b86f6bb2442b31 = L.circleMarker(
                [57.0, 25.0],
                {"bubblingMouseEvents": true, "color": "yellow", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "yellow", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7.29122433698562, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_4eaba77c815c49823a6b66a764a452f2 = L.popup({"maxWidth": "100%"});

        
            var html_292fa1d75427b0ce86462f18e538c003 = $(`<div id="html_292fa1d75427b0ce86462f18e538c003" style="width: 100.0%; height: 100.0%;">Latvia: 3.64561216849281 metric tons per capita</div>`)[0];
            popup_4eaba77c815c49823a6b66a764a452f2.setContent(html_292fa1d75427b0ce86462f18e538c003);
        

        circle_marker_032c48d911e53ca096b86f6bb2442b31.bindPopup(popup_4eaba77c815c49823a6b66a764a452f2)
        ;

        
    
    
            var circle_marker_cb9c8bc2b53ac330f209dd34d8a712e5 = L.circleMarker(
                [32.0, -5.0],
                {"bubblingMouseEvents": true, "color": "green", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "green", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3.63705277461998, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_3e2afc1fa1c7516d99c6cac789991860 = L.popup({"maxWidth": "100%"});

        
            var html_cadd02e9907137b4d3ace3c0cedb1d3b = $(`<div id="html_cadd02e9907137b4d3ace3c0cedb1d3b" style="width: 100.0%; height: 100.0%;">Morocco: 1.81852638730999 metric tons per capita</div>`)[0];
            popup_3e2afc1fa1c7516d99c6cac789991860.setContent(html_cadd02e9907137b4d3ace3c0cedb1d3b);
        

        circle_marker_cb9c8bc2b53ac330f209dd34d8a712e5.bindPopup(popup_3e2afc1fa1c7516d99c6cac789991860)
        ;

        
    
    
            var circle_marker_e3a342b63501c1307663a97cf22eecbd = L.circleMarker(
                [47.0, 29.0],
                {"bubblingMouseEvents": true, "color": "yellow", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "yellow", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 6.53569273622174, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_fbd73d5cb32c9d0e0fe09dd752ff7186 = L.popup({"maxWidth": "100%"});

        
            var html_a60ee86f8bfd5ee31b1b6ad0ea4dcc56 = $(`<div id="html_a60ee86f8bfd5ee31b1b6ad0ea4dcc56" style="width: 100.0%; height: 100.0%;">Moldova: 3.26784636811087 metric tons per capita</div>`)[0];
            popup_fbd73d5cb32c9d0e0fe09dd752ff7186.setContent(html_a60ee86f8bfd5ee31b1b6ad0ea4dcc56);
        

        circle_marker_e3a342b63501c1307663a97cf22eecbd.bindPopup(popup_fbd73d5cb32c9d0e0fe09dd752ff7186)
        ;

        
    
    
            var circle_marker_415bc2620ac4a5897f6276af26eb0151 = L.circleMarker(
                [-20.0, 47.0],
                {"bubblingMouseEvents": true, "color": "green", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "green", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 0.1945390811898186, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_f97f36f9e96aff2c114fee8f005b6010 = L.popup({"maxWidth": "100%"});

        
            var html_163eb3a63e3bec553add27de6288d4ad = $(`<div id="html_163eb3a63e3bec553add27de6288d4ad" style="width: 100.0%; height: 100.0%;">Madagascar: 0.0972695405949093 metric tons per capita</div>`)[0];
            popup_f97f36f9e96aff2c114fee8f005b6010.setContent(html_163eb3a63e3bec553add27de6288d4ad);
        

        circle_marker_415bc2620ac4a5897f6276af26eb0151.bindPopup(popup_f97f36f9e96aff2c114fee8f005b6010)
        ;

        
    
    
            var circle_marker_012b9c356454f1fe3b7ca1c2e7858bf9 = L.circleMarker(
                [3.25, 73.0],
                {"bubblingMouseEvents": true, "color": "green", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "green", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 5.65277059626232, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_552a618834b67ed219ebd94b98e0f046 = L.popup({"maxWidth": "100%"});

        
            var html_1cbf4ae7d33c5d5931a6110a76807013 = $(`<div id="html_1cbf4ae7d33c5d5931a6110a76807013" style="width: 100.0%; height: 100.0%;">Maldives: 2.82638529813116 metric tons per capita</div>`)[0];
            popup_552a618834b67ed219ebd94b98e0f046.setContent(html_1cbf4ae7d33c5d5931a6110a76807013);
        

        circle_marker_012b9c356454f1fe3b7ca1c2e7858bf9.bindPopup(popup_552a618834b67ed219ebd94b98e0f046)
        ;

        
    
    
            var circle_marker_5102de787a1cd18ab03051423b4112dc = L.circleMarker(
                [23.0, -102.0],
                {"bubblingMouseEvents": true, "color": "yellow", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "yellow", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 6.08153274954452, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_1002e4ef3c4f1956696d140910b173cf = L.popup({"maxWidth": "100%"});

        
            var html_8a480ce02a3ea4630fcdb5d69599940f = $(`<div id="html_8a480ce02a3ea4630fcdb5d69599940f" style="width: 100.0%; height: 100.0%;">Mexico: 3.04076637477226 metric tons per capita</div>`)[0];
            popup_1002e4ef3c4f1956696d140910b173cf.setContent(html_8a480ce02a3ea4630fcdb5d69599940f);
        

        circle_marker_5102de787a1cd18ab03051423b4112dc.bindPopup(popup_1002e4ef3c4f1956696d140910b173cf)
        ;

        
    
    
            var circle_marker_19bd490c1e9789b2d6a7b04b33208342 = L.circleMarker(
                [9.0, 168.0],
                {"bubblingMouseEvents": true, "color": "green", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "green", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 5.06760647732246, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_da219c216645d3a603208c375f0166a3 = L.popup({"maxWidth": "100%"});

        
            var html_650b0aa718214b4903e4d28e11a8b12f = $(`<div id="html_650b0aa718214b4903e4d28e11a8b12f" style="width: 100.0%; height: 100.0%;">Marshall Islands: 2.53380323866123 metric tons per capita</div>`)[0];
            popup_da219c216645d3a603208c375f0166a3.setContent(html_650b0aa718214b4903e4d28e11a8b12f);
        

        circle_marker_19bd490c1e9789b2d6a7b04b33208342.bindPopup(popup_da219c216645d3a603208c375f0166a3)
        ;

        
    
    
            var circle_marker_e14a29dba02dee127897bfe303aac099 = L.circleMarker(
                [41.8333, 22.0],
                {"bubblingMouseEvents": true, "color": "yellow", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "yellow", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7.32354088412196, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_e82ddf77f1aeae657c837987f9f0f6a7 = L.popup({"maxWidth": "100%"});

        
            var html_7912e71f2d5136ee92b883dfed885008 = $(`<div id="html_7912e71f2d5136ee92b883dfed885008" style="width: 100.0%; height: 100.0%;">North Macedonia: 3.66177044206098 metric tons per capita</div>`)[0];
            popup_e82ddf77f1aeae657c837987f9f0f6a7.setContent(html_7912e71f2d5136ee92b883dfed885008);
        

        circle_marker_e14a29dba02dee127897bfe303aac099.bindPopup(popup_e82ddf77f1aeae657c837987f9f0f6a7)
        ;

        
    
    
            var circle_marker_f5bf294bab66792803b1d70bafb32ebe = L.circleMarker(
                [17.0, -4.0],
                {"bubblingMouseEvents": true, "color": "green", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "green", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 0.391131942834634, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_88fb5c6c7f6f9184e04fb7d425e527ab = L.popup({"maxWidth": "100%"});

        
            var html_e47c1db21c3ac2ed099b0e0de41f0137 = $(`<div id="html_e47c1db21c3ac2ed099b0e0de41f0137" style="width: 100.0%; height: 100.0%;">Mali: 0.195565971417317 metric tons per capita</div>`)[0];
            popup_88fb5c6c7f6f9184e04fb7d425e527ab.setContent(html_e47c1db21c3ac2ed099b0e0de41f0137);
        

        circle_marker_f5bf294bab66792803b1d70bafb32ebe.bindPopup(popup_88fb5c6c7f6f9184e04fb7d425e527ab)
        ;

        
    
    
            var circle_marker_d925ea45280918f39a64e61b3827de3c = L.circleMarker(
                [35.8333, 14.5833],
                {"bubblingMouseEvents": true, "color": "yellow", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "yellow", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 6.25111578555184, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_083386836bd2c38f2e5cceae5bf2a9b7 = L.popup({"maxWidth": "100%"});

        
            var html_2303686033c364c9e09eb3968365964a = $(`<div id="html_2303686033c364c9e09eb3968365964a" style="width: 100.0%; height: 100.0%;">Malta: 3.12555789277592 metric tons per capita</div>`)[0];
            popup_083386836bd2c38f2e5cceae5bf2a9b7.setContent(html_2303686033c364c9e09eb3968365964a);
        

        circle_marker_d925ea45280918f39a64e61b3827de3c.bindPopup(popup_083386836bd2c38f2e5cceae5bf2a9b7)
        ;

        
    
    
            var circle_marker_8378485f1b27ae973319d65e66b33a74 = L.circleMarker(
                [22.0, 98.0],
                {"bubblingMouseEvents": true, "color": "green", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "green", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1.268160696781948, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_81b33b06c08524df07d229919f8a5ff3 = L.popup({"maxWidth": "100%"});

        
            var html_fbeb747dba5e5f500d87c97071ca507f = $(`<div id="html_fbeb747dba5e5f500d87c97071ca507f" style="width: 100.0%; height: 100.0%;">Myanmar: 0.634080348390974 metric tons per capita</div>`)[0];
            popup_81b33b06c08524df07d229919f8a5ff3.setContent(html_fbeb747dba5e5f500d87c97071ca507f);
        

        circle_marker_8378485f1b27ae973319d65e66b33a74.bindPopup(popup_81b33b06c08524df07d229919f8a5ff3)
        ;

        
    
    
            var circle_marker_4df5e3f5825af2447f6d30d0f9944393 = L.circleMarker(
                [42.0, 19.0],
                {"bubblingMouseEvents": true, "color": "yellow", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "yellow", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8.13512182402874, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_901640b80fda80ac63407fd9f2094ede = L.popup({"maxWidth": "100%"});

        
            var html_88ff17dbe2ec6cd2d80b15d7edcde970 = $(`<div id="html_88ff17dbe2ec6cd2d80b15d7edcde970" style="width: 100.0%; height: 100.0%;">Montenegro: 4.06756091201437 metric tons per capita</div>`)[0];
            popup_901640b80fda80ac63407fd9f2094ede.setContent(html_88ff17dbe2ec6cd2d80b15d7edcde970);
        

        circle_marker_4df5e3f5825af2447f6d30d0f9944393.bindPopup(popup_901640b80fda80ac63407fd9f2094ede)
        ;

        
    
    
            var circle_marker_2cf67ff258f9394c189b934e0f62253f = L.circleMarker(
                [46.0, 105.0],
                {"bubblingMouseEvents": true, "color": "orange", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "orange", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 12.86129067019596, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_7b1abc6836234acd9354a749beca10e8 = L.popup({"maxWidth": "100%"});

        
            var html_19bf3cc55919f30a92d04821ab778fe5 = $(`<div id="html_19bf3cc55919f30a92d04821ab778fe5" style="width: 100.0%; height: 100.0%;">Mongolia: 6.43064533509798 metric tons per capita</div>`)[0];
            popup_7b1abc6836234acd9354a749beca10e8.setContent(html_19bf3cc55919f30a92d04821ab778fe5);
        

        circle_marker_2cf67ff258f9394c189b934e0f62253f.bindPopup(popup_7b1abc6836234acd9354a749beca10e8)
        ;

        
    
    
            var circle_marker_4c8219e10e20255a5ae082e28e08dc6b = L.circleMarker(
                [-18.25, 35.0],
                {"bubblingMouseEvents": true, "color": "green", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "green", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 0.445535105430426, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_0e945680468f3142dcd48ceab7056d27 = L.popup({"maxWidth": "100%"});

        
            var html_c691ef0536528be96eaa051de830e75e = $(`<div id="html_c691ef0536528be96eaa051de830e75e" style="width: 100.0%; height: 100.0%;">Mozambique: 0.222767552715213 metric tons per capita</div>`)[0];
            popup_0e945680468f3142dcd48ceab7056d27.setContent(html_c691ef0536528be96eaa051de830e75e);
        

        circle_marker_4c8219e10e20255a5ae082e28e08dc6b.bindPopup(popup_0e945680468f3142dcd48ceab7056d27)
        ;

        
    
    
            var circle_marker_5b8b249ff82143da8d2962ae4debd059 = L.circleMarker(
                [20.0, -12.0],
                {"bubblingMouseEvents": true, "color": "green", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "green", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1.710352811672244, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_874d40a714f06003ac921bfe0afa5371 = L.popup({"maxWidth": "100%"});

        
            var html_eb018f3fff72a85d16acd04ed1169a9b = $(`<div id="html_eb018f3fff72a85d16acd04ed1169a9b" style="width: 100.0%; height: 100.0%;">Mauritania: 0.855176405836122 metric tons per capita</div>`)[0];
            popup_874d40a714f06003ac921bfe0afa5371.setContent(html_eb018f3fff72a85d16acd04ed1169a9b);
        

        circle_marker_5b8b249ff82143da8d2962ae4debd059.bindPopup(popup_874d40a714f06003ac921bfe0afa5371)
        ;

        
    
    
            var circle_marker_06f93a9e6e0d30cc71517a73a342e119 = L.circleMarker(
                [-20.2833, 57.55],
                {"bubblingMouseEvents": true, "color": "green", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "green", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 5.87702821611768, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_a080fb8088486fd69599fa05b482dfd5 = L.popup({"maxWidth": "100%"});

        
            var html_5596cfa0af983afa823c9cf2c402ccc0 = $(`<div id="html_5596cfa0af983afa823c9cf2c402ccc0" style="width: 100.0%; height: 100.0%;">Mauritius: 2.93851410805884 metric tons per capita</div>`)[0];
            popup_a080fb8088486fd69599fa05b482dfd5.setContent(html_5596cfa0af983afa823c9cf2c402ccc0);
        

        circle_marker_06f93a9e6e0d30cc71517a73a342e119.bindPopup(popup_a080fb8088486fd69599fa05b482dfd5)
        ;

        
    
    
            var circle_marker_a3261b9d1427f4ca1849ecb053d9eedd = L.circleMarker(
                [-13.5, 34.0],
                {"bubblingMouseEvents": true, "color": "green", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "green", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 0.1692723163745008, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_f7d6a3d0c8edd32c46023e5228aa3811 = L.popup({"maxWidth": "100%"});

        
            var html_fb09093e75d7a154bb1db84da7cbaa5d = $(`<div id="html_fb09093e75d7a154bb1db84da7cbaa5d" style="width: 100.0%; height: 100.0%;">Malawi: 0.0846361581872504 metric tons per capita</div>`)[0];
            popup_f7d6a3d0c8edd32c46023e5228aa3811.setContent(html_fb09093e75d7a154bb1db84da7cbaa5d);
        

        circle_marker_a3261b9d1427f4ca1849ecb053d9eedd.bindPopup(popup_f7d6a3d0c8edd32c46023e5228aa3811)
        ;

        
    
    
            var circle_marker_23185e642372bd0c9f122503ed9a2326 = L.circleMarker(
                [2.5, 112.5],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "red", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 14.7674308244583, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_a8d4e198065171719e2b2c57905cf861 = L.popup({"maxWidth": "100%"});

        
            var html_9de91307c2ad8a7e91f8a11d0b291184 = $(`<div id="html_9de91307c2ad8a7e91f8a11d0b291184" style="width: 100.0%; height: 100.0%;">Malaysia: 7.38371541222915 metric tons per capita</div>`)[0];
            popup_a8d4e198065171719e2b2c57905cf861.setContent(html_9de91307c2ad8a7e91f8a11d0b291184);
        

        circle_marker_23185e642372bd0c9f122503ed9a2326.bindPopup(popup_a8d4e198065171719e2b2c57905cf861)
        ;

        
    
    
            var circle_marker_ebcd9418519508f962d44a55906185d9 = L.circleMarker(
                [-22.0, 17.0],
                {"bubblingMouseEvents": true, "color": "green", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "green", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3.1760902945565, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_ef35a50c05c1887a6392092423c98ccd = L.popup({"maxWidth": "100%"});

        
            var html_b98b99852abc73e04cb06be48e3a6b8c = $(`<div id="html_b98b99852abc73e04cb06be48e3a6b8c" style="width: 100.0%; height: 100.0%;">Namibia: 1.58804514727825 metric tons per capita</div>`)[0];
            popup_ef35a50c05c1887a6392092423c98ccd.setContent(html_b98b99852abc73e04cb06be48e3a6b8c);
        

        circle_marker_ebcd9418519508f962d44a55906185d9.bindPopup(popup_ef35a50c05c1887a6392092423c98ccd)
        ;

        
    
    
            var circle_marker_e68b29941bb0b91d0b1051100004f5f6 = L.circleMarker(
                [16.0, 8.0],
                {"bubblingMouseEvents": true, "color": "green", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "green", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 0.1806511553820618, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_af2c8478605e8e55f04932479754d6bc = L.popup({"maxWidth": "100%"});

        
            var html_4be3ce0bd66f67332040ad63cdcc6b2e = $(`<div id="html_4be3ce0bd66f67332040ad63cdcc6b2e" style="width: 100.0%; height: 100.0%;">Niger: 0.0903255776910309 metric tons per capita</div>`)[0];
            popup_af2c8478605e8e55f04932479754d6bc.setContent(html_4be3ce0bd66f67332040ad63cdcc6b2e);
        

        circle_marker_e68b29941bb0b91d0b1051100004f5f6.bindPopup(popup_af2c8478605e8e55f04932479754d6bc)
        ;

        
    
    
            var circle_marker_e5d4c724d55d63ac7dad067a248aa801 = L.circleMarker(
                [10.0, 8.0],
                {"bubblingMouseEvents": true, "color": "green", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "green", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1.075020350779102, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_beea5cdf726f5eaf7e2dc711f8b59ac6 = L.popup({"maxWidth": "100%"});

        
            var html_8769a2ec8552bb1e8a6815c1a0237009 = $(`<div id="html_8769a2ec8552bb1e8a6815c1a0237009" style="width: 100.0%; height: 100.0%;">Nigeria: 0.537510175389551 metric tons per capita</div>`)[0];
            popup_beea5cdf726f5eaf7e2dc711f8b59ac6.setContent(html_8769a2ec8552bb1e8a6815c1a0237009);
        

        circle_marker_e5d4c724d55d63ac7dad067a248aa801.bindPopup(popup_beea5cdf726f5eaf7e2dc711f8b59ac6)
        ;

        
    
    
            var circle_marker_6956910d5c774b0e1c7383f7b7357fb7 = L.circleMarker(
                [13.0, -85.0],
                {"bubblingMouseEvents": true, "color": "green", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "green", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1.356504208546758, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_bb655133fb7c85efe6d362cd72967b3d = L.popup({"maxWidth": "100%"});

        
            var html_b819ea49c4f92765f4b7a70e86fb5ece = $(`<div id="html_b819ea49c4f92765f4b7a70e86fb5ece" style="width: 100.0%; height: 100.0%;">Nicaragua: 0.678252104273379 metric tons per capita</div>`)[0];
            popup_bb655133fb7c85efe6d362cd72967b3d.setContent(html_b819ea49c4f92765f4b7a70e86fb5ece);
        

        circle_marker_6956910d5c774b0e1c7383f7b7357fb7.bindPopup(popup_bb655133fb7c85efe6d362cd72967b3d)
        ;

        
    
    
            var circle_marker_44e4030971b731d5f1abfa2f5dce956b = L.circleMarker(
                [52.5, 5.75],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "red", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 14.9431069575438, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_7fa47a7edd09b6d40c1843745c728ff0 = L.popup({"maxWidth": "100%"});

        
            var html_44477fe9e9f9487f18c244aeb38eb1bb = $(`<div id="html_44477fe9e9f9487f18c244aeb38eb1bb" style="width: 100.0%; height: 100.0%;">Netherlands: 7.4715534787719 metric tons per capita</div>`)[0];
            popup_7fa47a7edd09b6d40c1843745c728ff0.setContent(html_44477fe9e9f9487f18c244aeb38eb1bb);
        

        circle_marker_44e4030971b731d5f1abfa2f5dce956b.bindPopup(popup_7fa47a7edd09b6d40c1843745c728ff0)
        ;

        
    
    
            var circle_marker_a8533eb9353cc631bf7808d978e8a0c3 = L.circleMarker(
                [62.0, 10.0],
                {"bubblingMouseEvents": true, "color": "orange", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "orange", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 13.4501600992662, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_feb33a8404ca317cea9578a118969bf8 = L.popup({"maxWidth": "100%"});

        
            var html_9c9656bba4f54499e26778d38688c089 = $(`<div id="html_9c9656bba4f54499e26778d38688c089" style="width: 100.0%; height: 100.0%;">Norway: 6.7250800496331 metric tons per capita</div>`)[0];
            popup_feb33a8404ca317cea9578a118969bf8.setContent(html_9c9656bba4f54499e26778d38688c089);
        

        circle_marker_a8533eb9353cc631bf7808d978e8a0c3.bindPopup(popup_feb33a8404ca317cea9578a118969bf8)
        ;

        
    
    
            var circle_marker_7a5840f435bb678c833958033917341e = L.circleMarker(
                [28.0, 84.0],
                {"bubblingMouseEvents": true, "color": "green", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "green", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1.018732494709208, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_e1d2bf078e874875af14f3d39b915421 = L.popup({"maxWidth": "100%"});

        
            var html_dd7c5ff837557878c4a23f90aa5697f1 = $(`<div id="html_dd7c5ff837557878c4a23f90aa5697f1" style="width: 100.0%; height: 100.0%;">Nepal: 0.509366247354604 metric tons per capita</div>`)[0];
            popup_e1d2bf078e874875af14f3d39b915421.setContent(html_dd7c5ff837557878c4a23f90aa5697f1);
        

        circle_marker_7a5840f435bb678c833958033917341e.bindPopup(popup_e1d2bf078e874875af14f3d39b915421)
        ;

        
    
    
            var circle_marker_22b9d74c00a3ecf0db43cd3945984557 = L.circleMarker(
                [-0.5333, 166.9167],
                {"bubblingMouseEvents": true, "color": "yellow", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "yellow", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 6.72350791717418, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_4fa5c4e6bd834dfd7c45500779c31735 = L.popup({"maxWidth": "100%"});

        
            var html_67662026745cfa8bb634a5a49092e988 = $(`<div id="html_67662026745cfa8bb634a5a49092e988" style="width: 100.0%; height: 100.0%;">Nauru: 3.36175395858709 metric tons per capita</div>`)[0];
            popup_4fa5c4e6bd834dfd7c45500779c31735.setContent(html_67662026745cfa8bb634a5a49092e988);
        

        circle_marker_22b9d74c00a3ecf0db43cd3945984557.bindPopup(popup_4fa5c4e6bd834dfd7c45500779c31735)
        ;

        
    
    
            var circle_marker_413359b945c88a03a83ea099611f80e4 = L.circleMarker(
                [-41.0, 174.0],
                {"bubblingMouseEvents": true, "color": "orange", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "orange", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 12.32159836548662, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_bb1b9e310e945a28c6ec97001a48c0c6 = L.popup({"maxWidth": "100%"});

        
            var html_98fd59b3a26d21a12216877fdbd91d93 = $(`<div id="html_98fd59b3a26d21a12216877fdbd91d93" style="width: 100.0%; height: 100.0%;">New Zealand: 6.16079918274331 metric tons per capita</div>`)[0];
            popup_bb1b9e310e945a28c6ec97001a48c0c6.setContent(html_98fd59b3a26d21a12216877fdbd91d93);
        

        circle_marker_413359b945c88a03a83ea099611f80e4.bindPopup(popup_bb1b9e310e945a28c6ec97001a48c0c6)
        ;

        
    
    
            var circle_marker_914cf22abc9e409562894c466c01e8db = L.circleMarker(
                [21.0, 57.0],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "red", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 31.272402005635, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_216ae617cc6078625b06e43b701bf969 = L.popup({"maxWidth": "100%"});

        
            var html_3258266c8e1f9520c34e132ec3009e63 = $(`<div id="html_3258266c8e1f9520c34e132ec3009e63" style="width: 100.0%; height: 100.0%;">Oman: 15.6362010028175 metric tons per capita</div>`)[0];
            popup_216ae617cc6078625b06e43b701bf969.setContent(html_3258266c8e1f9520c34e132ec3009e63);
        

        circle_marker_914cf22abc9e409562894c466c01e8db.bindPopup(popup_216ae617cc6078625b06e43b701bf969)
        ;

        
    
    
            var circle_marker_e4705c464b07abda3bf3e2dc3d2f1729 = L.circleMarker(
                [30.0, 70.0],
                {"bubblingMouseEvents": true, "color": "green", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "green", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1.62072043102062, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_55e7d49d0bc72cac1618f03935f1b436 = L.popup({"maxWidth": "100%"});

        
            var html_1b2faa367cae3dd75002e01b879b135f = $(`<div id="html_1b2faa367cae3dd75002e01b879b135f" style="width: 100.0%; height: 100.0%;">Pakistan: 0.81036021551031 metric tons per capita</div>`)[0];
            popup_55e7d49d0bc72cac1618f03935f1b436.setContent(html_1b2faa367cae3dd75002e01b879b135f);
        

        circle_marker_e4705c464b07abda3bf3e2dc3d2f1729.bindPopup(popup_55e7d49d0bc72cac1618f03935f1b436)
        ;

        
    
    
            var circle_marker_1f96094dae88ba5a103a8b66b324b56b = L.circleMarker(
                [9.0, -80.0],
                {"bubblingMouseEvents": true, "color": "green", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "green", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 4.46288604963306, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_308d429a57a8fa48f501c143d1c38d4c = L.popup({"maxWidth": "100%"});

        
            var html_01eb45407f22aaddaffc70712b18c07e = $(`<div id="html_01eb45407f22aaddaffc70712b18c07e" style="width: 100.0%; height: 100.0%;">Panama: 2.23144302481653 metric tons per capita</div>`)[0];
            popup_308d429a57a8fa48f501c143d1c38d4c.setContent(html_01eb45407f22aaddaffc70712b18c07e);
        

        circle_marker_1f96094dae88ba5a103a8b66b324b56b.bindPopup(popup_308d429a57a8fa48f501c143d1c38d4c)
        ;

        
    
    
            var circle_marker_3153ef3cd2e0507a0f74b3fc7fc772a4 = L.circleMarker(
                [-10.0, -76.0],
                {"bubblingMouseEvents": true, "color": "green", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "green", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2.79713203723816, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_840c2e165fce39ff37de0de274a384a4 = L.popup({"maxWidth": "100%"});

        
            var html_8f99220068d71c9c0a00ca11a72c69c3 = $(`<div id="html_8f99220068d71c9c0a00ca11a72c69c3" style="width: 100.0%; height: 100.0%;">Peru: 1.39856601861908 metric tons per capita</div>`)[0];
            popup_840c2e165fce39ff37de0de274a384a4.setContent(html_8f99220068d71c9c0a00ca11a72c69c3);
        

        circle_marker_3153ef3cd2e0507a0f74b3fc7fc772a4.bindPopup(popup_840c2e165fce39ff37de0de274a384a4)
        ;

        
    
    
            var circle_marker_f8bb7af5903b3480cd84c8dc45ee0a11 = L.circleMarker(
                [13.0, 122.0],
                {"bubblingMouseEvents": true, "color": "green", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "green", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2.37935890334568, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_683427a6bcc448156bbdfe32e1563112 = L.popup({"maxWidth": "100%"});

        
            var html_cb2ff3db453971231bdd2b9566198079 = $(`<div id="html_cb2ff3db453971231bdd2b9566198079" style="width: 100.0%; height: 100.0%;">Philippines: 1.18967945167284 metric tons per capita</div>`)[0];
            popup_683427a6bcc448156bbdfe32e1563112.setContent(html_cb2ff3db453971231bdd2b9566198079);
        

        circle_marker_f8bb7af5903b3480cd84c8dc45ee0a11.bindPopup(popup_683427a6bcc448156bbdfe32e1563112)
        ;

        
    
    
            var circle_marker_415fb9207250e316ea65da87411ff8bf = L.circleMarker(
                [7.5, 134.5],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "red", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 17.60516358780324, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_27f841f5b7c5b1219cd2fd1d881a85b2 = L.popup({"maxWidth": "100%"});

        
            var html_50b546f2f02a9b59099d0ac8f5e7db49 = $(`<div id="html_50b546f2f02a9b59099d0ac8f5e7db49" style="width: 100.0%; height: 100.0%;">Palau: 8.80258179390162 metric tons per capita</div>`)[0];
            popup_27f841f5b7c5b1219cd2fd1d881a85b2.setContent(html_50b546f2f02a9b59099d0ac8f5e7db49);
        

        circle_marker_415fb9207250e316ea65da87411ff8bf.bindPopup(popup_27f841f5b7c5b1219cd2fd1d881a85b2)
        ;

        
    
    
            var circle_marker_845fd46b462cf2c2c10cd8f8e61ed38d = L.circleMarker(
                [-6.0, 147.0],
                {"bubblingMouseEvents": true, "color": "green", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "green", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1.12650313242335, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_df23d600d5462bea03355d4c6efda452 = L.popup({"maxWidth": "100%"});

        
            var html_b53c764c707ac5bc6d18edb6b3bdbb6c = $(`<div id="html_b53c764c707ac5bc6d18edb6b3bdbb6c" style="width: 100.0%; height: 100.0%;">Papua New Guinea: 0.563251566211675 metric tons per capita</div>`)[0];
            popup_df23d600d5462bea03355d4c6efda452.setContent(html_b53c764c707ac5bc6d18edb6b3bdbb6c);
        

        circle_marker_845fd46b462cf2c2c10cd8f8e61ed38d.bindPopup(popup_df23d600d5462bea03355d4c6efda452)
        ;

        
    
    
            var circle_marker_37d00165fd65ce988c298c959487ffbd = L.circleMarker(
                [52.0, 20.0],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "red", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 14.73512674585418, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_104a7a135dbd37ea96fb69eac840869b = L.popup({"maxWidth": "100%"});

        
            var html_d5938547a265103e5356f0ca3ef112a0 = $(`<div id="html_d5938547a265103e5356f0ca3ef112a0" style="width: 100.0%; height: 100.0%;">Poland: 7.36756337292709 metric tons per capita</div>`)[0];
            popup_104a7a135dbd37ea96fb69eac840869b.setContent(html_d5938547a265103e5356f0ca3ef112a0);
        

        circle_marker_37d00165fd65ce988c298c959487ffbd.bindPopup(popup_104a7a135dbd37ea96fb69eac840869b)
        ;

        
    
    
            var circle_marker_e2568a31b435ec7f4f6b2dee2d68adff = L.circleMarker(
                [40.0, 127.0],
                {"bubblingMouseEvents": true, "color": "green", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "green", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 4.05429723753006, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_e61e84434c43637d485d6408706afd8b = L.popup({"maxWidth": "100%"});

        
            var html_1099f53d4639ba7350b2a7ea7aaf3437 = $(`<div id="html_1099f53d4639ba7350b2a7ea7aaf3437" style="width: 100.0%; height: 100.0%;">Korea, Democratic People's Republic of: 2.02714861876503 metric tons per capita</div>`)[0];
            popup_e61e84434c43637d485d6408706afd8b.setContent(html_1099f53d4639ba7350b2a7ea7aaf3437);
        

        circle_marker_e2568a31b435ec7f4f6b2dee2d68adff.bindPopup(popup_e61e84434c43637d485d6408706afd8b)
        ;

        
    
    
            var circle_marker_90e1b8c013e0283d3d0636882972ea88 = L.circleMarker(
                [39.5, -8.0],
                {"bubblingMouseEvents": true, "color": "yellow", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "yellow", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7.56981517383422, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_f8692fb254676d4d10e215f46c01e23c = L.popup({"maxWidth": "100%"});

        
            var html_3693f20330f7eb6d03c9eef20f884c54 = $(`<div id="html_3693f20330f7eb6d03c9eef20f884c54" style="width: 100.0%; height: 100.0%;">Portugal: 3.78490758691711 metric tons per capita</div>`)[0];
            popup_f8692fb254676d4d10e215f46c01e23c.setContent(html_3693f20330f7eb6d03c9eef20f884c54);
        

        circle_marker_90e1b8c013e0283d3d0636882972ea88.bindPopup(popup_f8692fb254676d4d10e215f46c01e23c)
        ;

        
    
    
            var circle_marker_45e527e567fc573678a9010cb7ec6fb4 = L.circleMarker(
                [-23.0, -58.0],
                {"bubblingMouseEvents": true, "color": "green", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "green", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2.28918238414068, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_6af661dc7cfa39b30e3aa67401e89b96 = L.popup({"maxWidth": "100%"});

        
            var html_101523bb45cf97eb3a743055e1f79cfd = $(`<div id="html_101523bb45cf97eb3a743055e1f79cfd" style="width: 100.0%; height: 100.0%;">Paraguay: 1.14459119207034 metric tons per capita</div>`)[0];
            popup_6af661dc7cfa39b30e3aa67401e89b96.setContent(html_101523bb45cf97eb3a743055e1f79cfd);
        

        circle_marker_45e527e567fc573678a9010cb7ec6fb4.bindPopup(popup_6af661dc7cfa39b30e3aa67401e89b96)
        ;

        
    
    
            var circle_marker_317bb0aa7caf0f997b1633068dd08f93 = L.circleMarker(
                [25.5, 51.25],
                {"bubblingMouseEvents": true, "color": "darkred", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "darkred", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 63.4536849026494, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_ea8fc1d334985d35b3db2e40d3fade60 = L.popup({"maxWidth": "100%"});

        
            var html_61512e60df52757e8cd209d75eec12a1 = $(`<div id="html_61512e60df52757e8cd209d75eec12a1" style="width: 100.0%; height: 100.0%;">Qatar: 31.7268424513247 metric tons per capita</div>`)[0];
            popup_ea8fc1d334985d35b3db2e40d3fade60.setContent(html_61512e60df52757e8cd209d75eec12a1);
        

        circle_marker_317bb0aa7caf0f997b1633068dd08f93.bindPopup(popup_ea8fc1d334985d35b3db2e40d3fade60)
        ;

        
    
    
            var circle_marker_a6e95a6bdf7b4533a90b415e7cad6df9 = L.circleMarker(
                [46.0, 25.0],
                {"bubblingMouseEvents": true, "color": "yellow", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "yellow", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7.12827500291976, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_8bfaf72aa9070b2354280e6649b4b3f9 = L.popup({"maxWidth": "100%"});

        
            var html_835055adf2afecd7d2adf648a2e56db8 = $(`<div id="html_835055adf2afecd7d2adf648a2e56db8" style="width: 100.0%; height: 100.0%;">Romania: 3.56413750145988 metric tons per capita</div>`)[0];
            popup_8bfaf72aa9070b2354280e6649b4b3f9.setContent(html_835055adf2afecd7d2adf648a2e56db8);
        

        circle_marker_a6e95a6bdf7b4533a90b415e7cad6df9.bindPopup(popup_8bfaf72aa9070b2354280e6649b4b3f9)
        ;

        
    
    
            var circle_marker_bfd48ada663e089feb9e5129a8e1e8a7 = L.circleMarker(
                [60.0, 100.0],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "red", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 22.2833054636702, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_6e1494169dd02c49d84802f05ce2eabf = L.popup({"maxWidth": "100%"});

        
            var html_a8d99e70134a315458e25d74c8ad0407 = $(`<div id="html_a8d99e70134a315458e25d74c8ad0407" style="width: 100.0%; height: 100.0%;">Russian Federation: 11.1416527318351 metric tons per capita</div>`)[0];
            popup_6e1494169dd02c49d84802f05ce2eabf.setContent(html_a8d99e70134a315458e25d74c8ad0407);
        

        circle_marker_bfd48ada663e089feb9e5129a8e1e8a7.bindPopup(popup_6e1494169dd02c49d84802f05ce2eabf)
        ;

        
    
    
            var circle_marker_ab86fd3ee81329d6ef37d434e3590e27 = L.circleMarker(
                [-2.0, 30.0],
                {"bubblingMouseEvents": true, "color": "green", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "green", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 0.210248280094524, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_f6d66a14da7d78c5fc9d1e5989e57991 = L.popup({"maxWidth": "100%"});

        
            var html_b710108a056c362a47db3ff47ad419e4 = $(`<div id="html_b710108a056c362a47db3ff47ad419e4" style="width: 100.0%; height: 100.0%;">Rwanda: 0.105124140047262 metric tons per capita</div>`)[0];
            popup_f6d66a14da7d78c5fc9d1e5989e57991.setContent(html_b710108a056c362a47db3ff47ad419e4);
        

        circle_marker_ab86fd3ee81329d6ef37d434e3590e27.bindPopup(popup_f6d66a14da7d78c5fc9d1e5989e57991)
        ;

        
    
    
            var circle_marker_7bbe92564f87056127252ee1b6d25629 = L.circleMarker(
                [25.0, 45.0],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "red", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 28.5331707350816, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_d4ad47f05852c1850b54e2ed22148a3f = L.popup({"maxWidth": "100%"});

        
            var html_aaa71e3b3c8fc7c6938287282a524084 = $(`<div id="html_aaa71e3b3c8fc7c6938287282a524084" style="width: 100.0%; height: 100.0%;">Saudi Arabia: 14.2665853675408 metric tons per capita</div>`)[0];
            popup_d4ad47f05852c1850b54e2ed22148a3f.setContent(html_aaa71e3b3c8fc7c6938287282a524084);
        

        circle_marker_7bbe92564f87056127252ee1b6d25629.bindPopup(popup_d4ad47f05852c1850b54e2ed22148a3f)
        ;

        
    
    
            var circle_marker_537496b2181e1e07e111bb781b114640 = L.circleMarker(
                [15.0, 30.0],
                {"bubblingMouseEvents": true, "color": "green", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "green", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 0.935907856633252, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_59b42271cd2668766b9a960dca1c9d67 = L.popup({"maxWidth": "100%"});

        
            var html_ce24b01b22fb8bf565e08913d31f39f1 = $(`<div id="html_ce24b01b22fb8bf565e08913d31f39f1" style="width: 100.0%; height: 100.0%;">Sudan: 0.467953928316626 metric tons per capita</div>`)[0];
            popup_59b42271cd2668766b9a960dca1c9d67.setContent(html_ce24b01b22fb8bf565e08913d31f39f1);
        

        circle_marker_537496b2181e1e07e111bb781b114640.bindPopup(popup_59b42271cd2668766b9a960dca1c9d67)
        ;

        
    
    
            var circle_marker_bf619a61cbb2564da73c52f0f8f95866 = L.circleMarker(
                [14.0, -14.0],
                {"bubblingMouseEvents": true, "color": "green", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "green", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1.299601122406018, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_d263d5a26cda80022037763b033ca4cf = L.popup({"maxWidth": "100%"});

        
            var html_0c13eadadddacd737909b37098be7a5b = $(`<div id="html_0c13eadadddacd737909b37098be7a5b" style="width: 100.0%; height: 100.0%;">Senegal: 0.649800561203009 metric tons per capita</div>`)[0];
            popup_d263d5a26cda80022037763b033ca4cf.setContent(html_0c13eadadddacd737909b37098be7a5b);
        

        circle_marker_bf619a61cbb2564da73c52f0f8f95866.bindPopup(popup_d263d5a26cda80022037763b033ca4cf)
        ;

        
    
    
            var circle_marker_b802119dd759daccfa5611820b897ee2 = L.circleMarker(
                [1.3667, 103.8],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "red", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 15.37336740413454, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_91fe4c4e5b6401c6d812a279f511501f = L.popup({"maxWidth": "100%"});

        
            var html_28d63e03d57a7a1fb465275e04829631 = $(`<div id="html_28d63e03d57a7a1fb465275e04829631" style="width: 100.0%; height: 100.0%;">Singapore: 7.68668370206727 metric tons per capita</div>`)[0];
            popup_91fe4c4e5b6401c6d812a279f511501f.setContent(html_28d63e03d57a7a1fb465275e04829631);
        

        circle_marker_b802119dd759daccfa5611820b897ee2.bindPopup(popup_91fe4c4e5b6401c6d812a279f511501f)
        ;

        
    
    
            var circle_marker_0a402c1832c92289d260c107aee9535a = L.circleMarker(
                [-8.0, 159.0],
                {"bubblingMouseEvents": true, "color": "green", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "green", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 0.646131098350528, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_08be573a8a303a322180b1d89db41169 = L.popup({"maxWidth": "100%"});

        
            var html_18c829ad84a506ac41fade169b604a6d = $(`<div id="html_18c829ad84a506ac41fade169b604a6d" style="width: 100.0%; height: 100.0%;">Solomon Islands: 0.323065549175264 metric tons per capita</div>`)[0];
            popup_08be573a8a303a322180b1d89db41169.setContent(html_18c829ad84a506ac41fade169b604a6d);
        

        circle_marker_0a402c1832c92289d260c107aee9535a.bindPopup(popup_08be573a8a303a322180b1d89db41169)
        ;

        
    
    
            var circle_marker_d9d87ca4b629041f49421fc3f374467a = L.circleMarker(
                [8.5, -11.5],
                {"bubblingMouseEvents": true, "color": "green", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "green", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 0.254555214556284, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_8bf44a82eb707c5684b6817d2b545e70 = L.popup({"maxWidth": "100%"});

        
            var html_302aa40ff58fe6ad6c3b4d14660b33da = $(`<div id="html_302aa40ff58fe6ad6c3b4d14660b33da" style="width: 100.0%; height: 100.0%;">Sierra Leone: 0.127277607278142 metric tons per capita</div>`)[0];
            popup_8bf44a82eb707c5684b6817d2b545e70.setContent(html_302aa40ff58fe6ad6c3b4d14660b33da);
        

        circle_marker_d9d87ca4b629041f49421fc3f374467a.bindPopup(popup_8bf44a82eb707c5684b6817d2b545e70)
        ;

        
    
    
            var circle_marker_927d33c9fa54cf4d9093e872ede58671 = L.circleMarker(
                [13.8333, -88.9167],
                {"bubblingMouseEvents": true, "color": "green", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "green", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2.02656048701272, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_128f2ea07286c6337439e81d762988c4 = L.popup({"maxWidth": "100%"});

        
            var html_7593530d135df21b1fc9d56697464121 = $(`<div id="html_7593530d135df21b1fc9d56697464121" style="width: 100.0%; height: 100.0%;">El Salvador: 1.01328024350636 metric tons per capita</div>`)[0];
            popup_128f2ea07286c6337439e81d762988c4.setContent(html_7593530d135df21b1fc9d56697464121);
        

        circle_marker_927d33c9fa54cf4d9093e872ede58671.bindPopup(popup_128f2ea07286c6337439e81d762988c4)
        ;

        
    
    
            var circle_marker_ec75e612a408e7e050f6306bc3b4d5ea = L.circleMarker(
                [10.0, 49.0],
                {"bubblingMouseEvents": true, "color": "green", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "green", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 0.0798693065302712, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_95a9cfeb065dc0bfb6b310c35c030895 = L.popup({"maxWidth": "100%"});

        
            var html_10d7f22fe0ba9c7266f36ddd2fdff3fb = $(`<div id="html_10d7f22fe0ba9c7266f36ddd2fdff3fb" style="width: 100.0%; height: 100.0%;">Somalia: 0.0399346532651356 metric tons per capita</div>`)[0];
            popup_95a9cfeb065dc0bfb6b310c35c030895.setContent(html_10d7f22fe0ba9c7266f36ddd2fdff3fb);
        

        circle_marker_ec75e612a408e7e050f6306bc3b4d5ea.bindPopup(popup_95a9cfeb065dc0bfb6b310c35c030895)
        ;

        
    
    
            var circle_marker_32a98a3e415f97177da6bcc352756cb4 = L.circleMarker(
                [44.0, 21.0],
                {"bubblingMouseEvents": true, "color": "orange", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "orange", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 13.42903434435028, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_62bf7631146e07184de15625f0cd3f74 = L.popup({"maxWidth": "100%"});

        
            var html_0d6c7dd211d9f21afde065c78d4ed0f2 = $(`<div id="html_0d6c7dd211d9f21afde065c78d4ed0f2" style="width: 100.0%; height: 100.0%;">Serbia: 6.71451717217514 metric tons per capita</div>`)[0];
            popup_62bf7631146e07184de15625f0cd3f74.setContent(html_0d6c7dd211d9f21afde065c78d4ed0f2);
        

        circle_marker_32a98a3e415f97177da6bcc352756cb4.bindPopup(popup_62bf7631146e07184de15625f0cd3f74)
        ;

        
    
    
            var circle_marker_c5201318d7479ca36b38ff16e7ab9682 = L.circleMarker(
                [1.0, 7.0],
                {"bubblingMouseEvents": true, "color": "green", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "green", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1.290700280368274, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_18b52a6ff14247e5fb637c24245e84a7 = L.popup({"maxWidth": "100%"});

        
            var html_8a8b93cc5b828c42288c15c895cc45ad = $(`<div id="html_8a8b93cc5b828c42288c15c895cc45ad" style="width: 100.0%; height: 100.0%;">Sao Tome and Principe: 0.645350140184137 metric tons per capita</div>`)[0];
            popup_18b52a6ff14247e5fb637c24245e84a7.setContent(html_8a8b93cc5b828c42288c15c895cc45ad);
        

        circle_marker_c5201318d7479ca36b38ff16e7ab9682.bindPopup(popup_18b52a6ff14247e5fb637c24245e84a7)
        ;

        
    
    
            var circle_marker_426633f3cf5512853629a04dc2b424f9 = L.circleMarker(
                [4.0, -56.0],
                {"bubblingMouseEvents": true, "color": "yellow", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "yellow", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8.57015311375224, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_a5951dfacea0a833c58a90e2b25d7299 = L.popup({"maxWidth": "100%"});

        
            var html_4116a9c1f07c5ae30c636a25140889a6 = $(`<div id="html_4116a9c1f07c5ae30c636a25140889a6" style="width: 100.0%; height: 100.0%;">Suriname: 4.28507655687612 metric tons per capita</div>`)[0];
            popup_a5951dfacea0a833c58a90e2b25d7299.setContent(html_4116a9c1f07c5ae30c636a25140889a6);
        

        circle_marker_426633f3cf5512853629a04dc2b424f9.bindPopup(popup_a5951dfacea0a833c58a90e2b25d7299)
        ;

        
    
    
            var circle_marker_be6269976adea59ed239db45e88a15e6 = L.circleMarker(
                [48.6667, 19.5],
                {"bubblingMouseEvents": true, "color": "orange", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "orange", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 10.63810961585704, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_8220c4d06fede125a22c0b163b72feab = L.popup({"maxWidth": "100%"});

        
            var html_ac69413581179cf6455db9def85e8bd2 = $(`<div id="html_ac69413581179cf6455db9def85e8bd2" style="width: 100.0%; height: 100.0%;">Slovak Republic: 5.31905480792852 metric tons per capita</div>`)[0];
            popup_8220c4d06fede125a22c0b163b72feab.setContent(html_ac69413581179cf6455db9def85e8bd2);
        

        circle_marker_be6269976adea59ed239db45e88a15e6.bindPopup(popup_8220c4d06fede125a22c0b163b72feab)
        ;

        
    
    
            var circle_marker_0d796333a70e833fec4b65c995f6b73a = L.circleMarker(
                [46.0, 15.0],
                {"bubblingMouseEvents": true, "color": "orange", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "orange", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 11.86947035771652, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_3109541e5ba4e104b69cfeaa6dc3faee = L.popup({"maxWidth": "100%"});

        
            var html_ef701967eb32692af1f65fc1fc2f6eb4 = $(`<div id="html_ef701967eb32692af1f65fc1fc2f6eb4" style="width: 100.0%; height: 100.0%;">Slovenia: 5.93473517885826 metric tons per capita</div>`)[0];
            popup_3109541e5ba4e104b69cfeaa6dc3faee.setContent(html_ef701967eb32692af1f65fc1fc2f6eb4);
        

        circle_marker_0d796333a70e833fec4b65c995f6b73a.bindPopup(popup_3109541e5ba4e104b69cfeaa6dc3faee)
        ;

        
    
    
            var circle_marker_c573a6c17c4f0b7c04945b36ae3d039e = L.circleMarker(
                [62.0, 15.0],
                {"bubblingMouseEvents": true, "color": "yellow", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "yellow", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 6.48597828625494, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_2079acfe8519f66ee540d3e1250ecf6f = L.popup({"maxWidth": "100%"});

        
            var html_7968be1c69d53dbad5976bc7d1216520 = $(`<div id="html_7968be1c69d53dbad5976bc7d1216520" style="width: 100.0%; height: 100.0%;">Sweden: 3.24298914312747 metric tons per capita</div>`)[0];
            popup_2079acfe8519f66ee540d3e1250ecf6f.setContent(html_7968be1c69d53dbad5976bc7d1216520);
        

        circle_marker_c573a6c17c4f0b7c04945b36ae3d039e.bindPopup(popup_2079acfe8519f66ee540d3e1250ecf6f)
        ;

        
    
    
            var circle_marker_c92491ade3d1a81f8a121e6559c2386b = L.circleMarker(
                [-26.5, 31.5],
                {"bubblingMouseEvents": true, "color": "green", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "green", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1.944175055371806, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_0bf6b2e1cf0f5159b621d9b4f1f754ae = L.popup({"maxWidth": "100%"});

        
            var html_bcd1c87079341c17490468b56e6fdd68 = $(`<div id="html_bcd1c87079341c17490468b56e6fdd68" style="width: 100.0%; height: 100.0%;">Eswatini: 0.972087527685903 metric tons per capita</div>`)[0];
            popup_0bf6b2e1cf0f5159b621d9b4f1f754ae.setContent(html_bcd1c87079341c17490468b56e6fdd68);
        

        circle_marker_c92491ade3d1a81f8a121e6559c2386b.bindPopup(popup_0bf6b2e1cf0f5159b621d9b4f1f754ae)
        ;

        
    
    
            var circle_marker_4caac1228ad7ccf782bb8752cdc13be7 = L.circleMarker(
                [-4.5833, 55.6667],
                {"bubblingMouseEvents": true, "color": "orange", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "orange", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 12.16103674514026, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_535f7cb884d72d1df88368eeac88b628 = L.popup({"maxWidth": "100%"});

        
            var html_6a0fb38784a033e1bcae67f24f1b6af4 = $(`<div id="html_6a0fb38784a033e1bcae67f24f1b6af4" style="width: 100.0%; height: 100.0%;">Seychelles: 6.08051837257013 metric tons per capita</div>`)[0];
            popup_535f7cb884d72d1df88368eeac88b628.setContent(html_6a0fb38784a033e1bcae67f24f1b6af4);
        

        circle_marker_4caac1228ad7ccf782bb8752cdc13be7.bindPopup(popup_535f7cb884d72d1df88368eeac88b628)
        ;

        
    
    
            var circle_marker_e025c8e3639002df787715d3384e2f3d = L.circleMarker(
                [35.0, 38.0],
                {"bubblingMouseEvents": true, "color": "green", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "green", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2.42960496750646, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_22a891a7c7867a49c6d608e85ca566a7 = L.popup({"maxWidth": "100%"});

        
            var html_88aec5b8f9c3c0a9335af6998304c59b = $(`<div id="html_88aec5b8f9c3c0a9335af6998304c59b" style="width: 100.0%; height: 100.0%;">Syrian Arab Republic: 1.21480248375323 metric tons per capita</div>`)[0];
            popup_22a891a7c7867a49c6d608e85ca566a7.setContent(html_88aec5b8f9c3c0a9335af6998304c59b);
        

        circle_marker_e025c8e3639002df787715d3384e2f3d.bindPopup(popup_22a891a7c7867a49c6d608e85ca566a7)
        ;

        
    
    
            var circle_marker_0dbf1d2425684eb8086a6229ecdd5aaf = L.circleMarker(
                [15.0, 19.0],
                {"bubblingMouseEvents": true, "color": "green", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "green", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 0.188456374193805, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_287d0c4d9170e4765174c38e4920c05d = L.popup({"maxWidth": "100%"});

        
            var html_9284289f9184b789cec212b90d5f9a72 = $(`<div id="html_9284289f9184b789cec212b90d5f9a72" style="width: 100.0%; height: 100.0%;">Chad: 0.0942281870969025 metric tons per capita</div>`)[0];
            popup_287d0c4d9170e4765174c38e4920c05d.setContent(html_9284289f9184b789cec212b90d5f9a72);
        

        circle_marker_0dbf1d2425684eb8086a6229ecdd5aaf.bindPopup(popup_287d0c4d9170e4765174c38e4920c05d)
        ;

        
    
    
            var circle_marker_c878a9a89b1878962002c99608213047 = L.circleMarker(
                [8.0, 1.1667],
                {"bubblingMouseEvents": true, "color": "green", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "green", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 0.572123687308856, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_96f6431eb7239de6918229ebdf4a525b = L.popup({"maxWidth": "100%"});

        
            var html_6f188258b1dfce6ba2478554ee2f5e7d = $(`<div id="html_6f188258b1dfce6ba2478554ee2f5e7d" style="width: 100.0%; height: 100.0%;">Togo: 0.286061843654428 metric tons per capita</div>`)[0];
            popup_96f6431eb7239de6918229ebdf4a525b.setContent(html_6f188258b1dfce6ba2478554ee2f5e7d);
        

        circle_marker_c878a9a89b1878962002c99608213047.bindPopup(popup_96f6431eb7239de6918229ebdf4a525b)
        ;

        
    
    
            var circle_marker_e95f939b7a22d9c6e97fa2cbb8e284e9 = L.circleMarker(
                [15.0, 100.0],
                {"bubblingMouseEvents": true, "color": "yellow", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "yellow", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7.42851161200824, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_a0739d11f1ac2f6c8b71c2d1a6a71236 = L.popup({"maxWidth": "100%"});

        
            var html_35a501c7c0a0f49361a4d78bf08488ec = $(`<div id="html_35a501c7c0a0f49361a4d78bf08488ec" style="width: 100.0%; height: 100.0%;">Thailand: 3.71425580600412 metric tons per capita</div>`)[0];
            popup_a0739d11f1ac2f6c8b71c2d1a6a71236.setContent(html_35a501c7c0a0f49361a4d78bf08488ec);
        

        circle_marker_e95f939b7a22d9c6e97fa2cbb8e284e9.bindPopup(popup_a0739d11f1ac2f6c8b71c2d1a6a71236)
        ;

        
    
    
            var circle_marker_565f959c0ad50849efd2dc8eae0a34c3 = L.circleMarker(
                [39.0, 71.0],
                {"bubblingMouseEvents": true, "color": "green", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "green", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1.955066048551602, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_e04241d653dd89ce5ff11879f07907b4 = L.popup({"maxWidth": "100%"});

        
            var html_a70bf0bf3e6364dc94e8f9310d8f5366 = $(`<div id="html_a70bf0bf3e6364dc94e8f9310d8f5366" style="width: 100.0%; height: 100.0%;">Tajikistan: 0.977533024275801 metric tons per capita</div>`)[0];
            popup_e04241d653dd89ce5ff11879f07907b4.setContent(html_a70bf0bf3e6364dc94e8f9310d8f5366);
        

        circle_marker_565f959c0ad50849efd2dc8eae0a34c3.bindPopup(popup_e04241d653dd89ce5ff11879f07907b4)
        ;

        
    
    
            var circle_marker_5307edf6baa2c14dd31a5c21ea3f58ac = L.circleMarker(
                [40.0, 60.0],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "red", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 20.3681725984642, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_c08152eb873c5dafe852d94437796170 = L.popup({"maxWidth": "100%"});

        
            var html_904fe8ceec23e1b6302fb14e7918d2ba = $(`<div id="html_904fe8ceec23e1b6302fb14e7918d2ba" style="width: 100.0%; height: 100.0%;">Turkmenistan: 10.1840862992321 metric tons per capita</div>`)[0];
            popup_c08152eb873c5dafe852d94437796170.setContent(html_904fe8ceec23e1b6302fb14e7918d2ba);
        

        circle_marker_5307edf6baa2c14dd31a5c21ea3f58ac.bindPopup(popup_c08152eb873c5dafe852d94437796170)
        ;

        
    
    
            var circle_marker_c26ddb316f581365039992d89c2956e0 = L.circleMarker(
                [-8.55, 125.5167],
                {"bubblingMouseEvents": true, "color": "green", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "green", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 0.686310331962816, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_9246397863f3fc2af79826c7b15b398f = L.popup({"maxWidth": "100%"});

        
            var html_76b31b794853fb729c7fb4bdbbbb24d1 = $(`<div id="html_76b31b794853fb729c7fb4bdbbbb24d1" style="width: 100.0%; height: 100.0%;">Timor-Leste: 0.343155165981408 metric tons per capita</div>`)[0];
            popup_9246397863f3fc2af79826c7b15b398f.setContent(html_76b31b794853fb729c7fb4bdbbbb24d1);
        

        circle_marker_c26ddb316f581365039992d89c2956e0.bindPopup(popup_9246397863f3fc2af79826c7b15b398f)
        ;

        
    
    
            var circle_marker_b6aa1c4c143c0d589418933a1d808058 = L.circleMarker(
                [-20.0, -175.0],
                {"bubblingMouseEvents": true, "color": "green", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "green", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2.24409523628556, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_3a22afb524c03864a33f47e85a9f8495 = L.popup({"maxWidth": "100%"});

        
            var html_e9b6813f7f96b8c71fc9022ed9fa87a9 = $(`<div id="html_e9b6813f7f96b8c71fc9022ed9fa87a9" style="width: 100.0%; height: 100.0%;">Tonga: 1.12204761814278 metric tons per capita</div>`)[0];
            popup_3a22afb524c03864a33f47e85a9f8495.setContent(html_e9b6813f7f96b8c71fc9022ed9fa87a9);
        

        circle_marker_b6aa1c4c143c0d589418933a1d808058.bindPopup(popup_3a22afb524c03864a33f47e85a9f8495)
        ;

        
    
    
            var circle_marker_0e78cfcc747cfc040f675c51e942016e = L.circleMarker(
                [11.0, -61.0],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "red", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 20.3142383445082, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_89f1025a47f84822c6d0a6330efca29c = L.popup({"maxWidth": "100%"});

        
            var html_bc262b1d1897bdcb6aee5571141a27cf = $(`<div id="html_bc262b1d1897bdcb6aee5571141a27cf" style="width: 100.0%; height: 100.0%;">Trinidad and Tobago: 10.1571191722541 metric tons per capita</div>`)[0];
            popup_89f1025a47f84822c6d0a6330efca29c.setContent(html_bc262b1d1897bdcb6aee5571141a27cf);
        

        circle_marker_0e78cfcc747cfc040f675c51e942016e.bindPopup(popup_89f1025a47f84822c6d0a6330efca29c)
        ;

        
    
    
            var circle_marker_49d1e0321fd80f05b3744b9dbcabe27d = L.circleMarker(
                [34.0, 9.0],
                {"bubblingMouseEvents": true, "color": "green", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "green", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 4.8172450564776, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_e1c13acecbbc35d2b6fba17cbd97f7dd = L.popup({"maxWidth": "100%"});

        
            var html_b4f833260a0734d99d5e267e6db62d86 = $(`<div id="html_b4f833260a0734d99d5e267e6db62d86" style="width: 100.0%; height: 100.0%;">Tunisia: 2.4086225282388 metric tons per capita</div>`)[0];
            popup_e1c13acecbbc35d2b6fba17cbd97f7dd.setContent(html_b4f833260a0734d99d5e267e6db62d86);
        

        circle_marker_49d1e0321fd80f05b3744b9dbcabe27d.bindPopup(popup_e1c13acecbbc35d2b6fba17cbd97f7dd)
        ;

        
    
    
            var circle_marker_dd570330514957745a5c9750ef2eec97 = L.circleMarker(
                [39.0, 35.0],
                {"bubblingMouseEvents": true, "color": "yellow", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "yellow", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 9.7717278521666, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_df329566b1924c0de5e12b1f1f315a7d = L.popup({"maxWidth": "100%"});

        
            var html_9d64b5b099cabffdfa8d7b5ad42478de = $(`<div id="html_9d64b5b099cabffdfa8d7b5ad42478de" style="width: 100.0%; height: 100.0%;">Türkiye: 4.8858639260833 metric tons per capita</div>`)[0];
            popup_df329566b1924c0de5e12b1f1f315a7d.setContent(html_9d64b5b099cabffdfa8d7b5ad42478de);
        

        circle_marker_dd570330514957745a5c9750ef2eec97.bindPopup(popup_df329566b1924c0de5e12b1f1f315a7d)
        ;

        
    
    
            var circle_marker_c53e5f7b3ee3cf85141709c69e974fce = L.circleMarker(
                [-8.0, 178.0],
                {"bubblingMouseEvents": true, "color": "green", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "green", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1.192519649471496, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_70976b72cf6d69c6eef40eb20a862ae6 = L.popup({"maxWidth": "100%"});

        
            var html_ca032d1d4d538d1cbceb9651ed3ad81b = $(`<div id="html_ca032d1d4d538d1cbceb9651ed3ad81b" style="width: 100.0%; height: 100.0%;">Tuvalu: 0.596259824735748 metric tons per capita</div>`)[0];
            popup_70976b72cf6d69c6eef40eb20a862ae6.setContent(html_ca032d1d4d538d1cbceb9651ed3ad81b);
        

        circle_marker_c53e5f7b3ee3cf85141709c69e974fce.bindPopup(popup_70976b72cf6d69c6eef40eb20a862ae6)
        ;

        
    
    
            var circle_marker_afe7cf5281c55abe7cb01ff3cae518b0 = L.circleMarker(
                [-6.0, 35.0],
                {"bubblingMouseEvents": true, "color": "green", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "green", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 0.46789118424035, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_bc8aaa2e3c433ddd11b3f52a676464fd = L.popup({"maxWidth": "100%"});

        
            var html_a39414ab300e16ae24735b35fed43ae7 = $(`<div id="html_a39414ab300e16ae24735b35fed43ae7" style="width: 100.0%; height: 100.0%;">Tanzania: 0.233945592120175 metric tons per capita</div>`)[0];
            popup_bc8aaa2e3c433ddd11b3f52a676464fd.setContent(html_a39414ab300e16ae24735b35fed43ae7);
        

        circle_marker_afe7cf5281c55abe7cb01ff3cae518b0.bindPopup(popup_bc8aaa2e3c433ddd11b3f52a676464fd)
        ;

        
    
    
            var circle_marker_919a1af56af07fd98851ff2a68e19ed0 = L.circleMarker(
                [1.0, 32.0],
                {"bubblingMouseEvents": true, "color": "green", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "green", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 0.255586069653892, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_deff115a4261f99045f07b18abf8750a = L.popup({"maxWidth": "100%"});

        
            var html_661be4474d4ec14e659f5f9754b0a32c = $(`<div id="html_661be4474d4ec14e659f5f9754b0a32c" style="width: 100.0%; height: 100.0%;">Uganda: 0.127793034826946 metric tons per capita</div>`)[0];
            popup_deff115a4261f99045f07b18abf8750a.setContent(html_661be4474d4ec14e659f5f9754b0a32c);
        

        circle_marker_919a1af56af07fd98851ff2a68e19ed0.bindPopup(popup_deff115a4261f99045f07b18abf8750a)
        ;

        
    
    
            var circle_marker_7d8820014a9458b7a203eb1cd7dde966 = L.circleMarker(
                [49.0, 32.0],
                {"bubblingMouseEvents": true, "color": "yellow", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "yellow", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7.4947756902556, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_0f5ba8e22dbca3bb916571107b08c1fd = L.popup({"maxWidth": "100%"});

        
            var html_52ec13f4cc7b35f812004246a10b950c = $(`<div id="html_52ec13f4cc7b35f812004246a10b950c" style="width: 100.0%; height: 100.0%;">Ukraine: 3.7473878451278 metric tons per capita</div>`)[0];
            popup_0f5ba8e22dbca3bb916571107b08c1fd.setContent(html_52ec13f4cc7b35f812004246a10b950c);
        

        circle_marker_7d8820014a9458b7a203eb1cd7dde966.bindPopup(popup_0f5ba8e22dbca3bb916571107b08c1fd)
        ;

        
    
    
            var circle_marker_af42a9971b7fea7f7445bdf120e5ce69 = L.circleMarker(
                [-33.0, -56.0],
                {"bubblingMouseEvents": true, "color": "green", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "green", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3.79943810099834, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_7648d5bcb0601d58ba338ee5e21aac61 = L.popup({"maxWidth": "100%"});

        
            var html_528729313a8896ad6f3c6b30e47a909c = $(`<div id="html_528729313a8896ad6f3c6b30e47a909c" style="width: 100.0%; height: 100.0%;">Uruguay: 1.89971905049917 metric tons per capita</div>`)[0];
            popup_7648d5bcb0601d58ba338ee5e21aac61.setContent(html_528729313a8896ad6f3c6b30e47a909c);
        

        circle_marker_af42a9971b7fea7f7445bdf120e5ce69.bindPopup(popup_7648d5bcb0601d58ba338ee5e21aac61)
        ;

        
    
    
            var circle_marker_b77ffd1066ae0d41cee13b3e789eb4a1 = L.circleMarker(
                [38.0, -97.0],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "red", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 26.0644434580524, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_9c4aca41f5a78e1fda5014fb29d93822 = L.popup({"maxWidth": "100%"});

        
            var html_0e548517c7c93a4264bd2f87be56d1ad = $(`<div id="html_0e548517c7c93a4264bd2f87be56d1ad" style="width: 100.0%; height: 100.0%;">United States: 13.0322217290262 metric tons per capita</div>`)[0];
            popup_9c4aca41f5a78e1fda5014fb29d93822.setContent(html_0e548517c7c93a4264bd2f87be56d1ad);
        

        circle_marker_b77ffd1066ae0d41cee13b3e789eb4a1.bindPopup(popup_9c4aca41f5a78e1fda5014fb29d93822)
        ;

        
    
    
            var circle_marker_97437bde41dce86da16f20f4f80dd5b6 = L.circleMarker(
                [41.0, 64.0],
                {"bubblingMouseEvents": true, "color": "yellow", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "yellow", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 6.75260757097516, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_e142f0c2f5cb1636299295687f41828a = L.popup({"maxWidth": "100%"});

        
            var html_fadb53699a1d52cf38cdded138060d76 = $(`<div id="html_fadb53699a1d52cf38cdded138060d76" style="width: 100.0%; height: 100.0%;">Uzbekistan: 3.37630378548758 metric tons per capita</div>`)[0];
            popup_e142f0c2f5cb1636299295687f41828a.setContent(html_fadb53699a1d52cf38cdded138060d76);
        

        circle_marker_97437bde41dce86da16f20f4f80dd5b6.bindPopup(popup_e142f0c2f5cb1636299295687f41828a)
        ;

        
    
    
            var circle_marker_8fe2103bd3316982a16c8d05bf4405cd = L.circleMarker(
                [13.25, -61.2],
                {"bubblingMouseEvents": true, "color": "green", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "green", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 4.201391543696, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_4560d33f85ef7c6cea8994fdeedb8096 = L.popup({"maxWidth": "100%"});

        
            var html_7b9a3c6474718a8240ada361d81d1673 = $(`<div id="html_7b9a3c6474718a8240ada361d81d1673" style="width: 100.0%; height: 100.0%;">St. Vincent and the Grenadines: 2.100695771848 metric tons per capita</div>`)[0];
            popup_4560d33f85ef7c6cea8994fdeedb8096.setContent(html_7b9a3c6474718a8240ada361d81d1673);
        

        circle_marker_8fe2103bd3316982a16c8d05bf4405cd.bindPopup(popup_4560d33f85ef7c6cea8994fdeedb8096)
        ;

        
    
    
            var circle_marker_e90f01c10d58f6c0739428589ebbf813 = L.circleMarker(
                [8.0, -66.0],
                {"bubblingMouseEvents": true, "color": "green", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "green", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 5.09005595663922, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_ebcc8c9ee6fe805271a9bf0112462078 = L.popup({"maxWidth": "100%"});

        
            var html_856ef4236f897594cd994d58c5c80901 = $(`<div id="html_856ef4236f897594cd994d58c5c80901" style="width: 100.0%; height: 100.0%;">Venezuela, RB: 2.54502797831961 metric tons per capita</div>`)[0];
            popup_ebcc8c9ee6fe805271a9bf0112462078.setContent(html_856ef4236f897594cd994d58c5c80901);
        

        circle_marker_e90f01c10d58f6c0739428589ebbf813.bindPopup(popup_ebcc8c9ee6fe805271a9bf0112462078)
        ;

        
    
    
            var circle_marker_bca96f8c7a69ae658c64d5effc8f57a3 = L.circleMarker(
                [16.0, 106.0],
                {"bubblingMouseEvents": true, "color": "yellow", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "yellow", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 7.35288017627968, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_a0cfe0b11ff969f71ebffd08a42c54fc = L.popup({"maxWidth": "100%"});

        
            var html_d150eec4565211d5132fca700e052c60 = $(`<div id="html_d150eec4565211d5132fca700e052c60" style="width: 100.0%; height: 100.0%;">Viet Nam: 3.67644008813984 metric tons per capita</div>`)[0];
            popup_a0cfe0b11ff969f71ebffd08a42c54fc.setContent(html_d150eec4565211d5132fca700e052c60);
        

        circle_marker_bca96f8c7a69ae658c64d5effc8f57a3.bindPopup(popup_a0cfe0b11ff969f71ebffd08a42c54fc)
        ;

        
    
    
            var circle_marker_51849fb1cee0e8fcdd4b81e27e424c79 = L.circleMarker(
                [-16.0, 167.0],
                {"bubblingMouseEvents": true, "color": "green", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "green", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 0.778349936634744, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_cfc43dff766c0cffe086da83e823b631 = L.popup({"maxWidth": "100%"});

        
            var html_4b10e222565b71026159d4763f3bc5b9 = $(`<div id="html_4b10e222565b71026159d4763f3bc5b9" style="width: 100.0%; height: 100.0%;">Vanuatu: 0.389174968317372 metric tons per capita</div>`)[0];
            popup_cfc43dff766c0cffe086da83e823b631.setContent(html_4b10e222565b71026159d4763f3bc5b9);
        

        circle_marker_51849fb1cee0e8fcdd4b81e27e424c79.bindPopup(popup_cfc43dff766c0cffe086da83e823b631)
        ;

        
    
    
            var circle_marker_85468e951a5d1426261d91ac2c9a2819 = L.circleMarker(
                [-13.5833, -172.3333],
                {"bubblingMouseEvents": true, "color": "green", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "green", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1.921564795816292, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_2aaf21ea3ee80c86d0dd9802e9021283 = L.popup({"maxWidth": "100%"});

        
            var html_83e80fb40d8f0cb3c62691397b11418c = $(`<div id="html_83e80fb40d8f0cb3c62691397b11418c" style="width: 100.0%; height: 100.0%;">Samoa: 0.960782397908146 metric tons per capita</div>`)[0];
            popup_2aaf21ea3ee80c86d0dd9802e9021283.setContent(html_83e80fb40d8f0cb3c62691397b11418c);
        

        circle_marker_85468e951a5d1426261d91ac2c9a2819.bindPopup(popup_2aaf21ea3ee80c86d0dd9802e9021283)
        ;

        
    
    
            var circle_marker_fff89c6fb9beea6a6859c402ce12ae6b = L.circleMarker(
                [15.0, 48.0],
                {"bubblingMouseEvents": true, "color": "green", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "green", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 0.617029228616512, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_ef599096c24d5033d45e06dd46097235 = L.popup({"maxWidth": "100%"});

        
            var html_3b495a770ff2fe305bf104ab4d93fdec = $(`<div id="html_3b495a770ff2fe305bf104ab4d93fdec" style="width: 100.0%; height: 100.0%;">Yemen, Rep.: 0.308514614308256 metric tons per capita</div>`)[0];
            popup_ef599096c24d5033d45e06dd46097235.setContent(html_3b495a770ff2fe305bf104ab4d93fdec);
        

        circle_marker_fff89c6fb9beea6a6859c402ce12ae6b.bindPopup(popup_ef599096c24d5033d45e06dd46097235)
        ;

        
    
    
            var circle_marker_189d96a4d17ed7ff407fd50932468568 = L.circleMarker(
                [-29.0, 24.0],
                {"bubblingMouseEvents": true, "color": "orange", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "orange", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 13.37512629475562, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_0514d92b6721513bcce19ede1f5f3cc7 = L.popup({"maxWidth": "100%"});

        
            var html_047bb8380181fefb934cef13b8139229 = $(`<div id="html_047bb8380181fefb934cef13b8139229" style="width: 100.0%; height: 100.0%;">South Africa: 6.68756314737781 metric tons per capita</div>`)[0];
            popup_0514d92b6721513bcce19ede1f5f3cc7.setContent(html_047bb8380181fefb934cef13b8139229);
        

        circle_marker_189d96a4d17ed7ff407fd50932468568.bindPopup(popup_0514d92b6721513bcce19ede1f5f3cc7)
        ;

        
    
    
            var circle_marker_7fe19439637eea431f12011de3a8aaa8 = L.circleMarker(
                [-15.0, 30.0],
                {"bubblingMouseEvents": true, "color": "green", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "green", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 0.80380542500772, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_ff30df4159ae77c6e4d070a69b7570b8 = L.popup({"maxWidth": "100%"});

        
            var html_645789c7a44bad5fe2db05f6b5519ece = $(`<div id="html_645789c7a44bad5fe2db05f6b5519ece" style="width: 100.0%; height: 100.0%;">Zambia: 0.40190271250386 metric tons per capita</div>`)[0];
            popup_ff30df4159ae77c6e4d070a69b7570b8.setContent(html_645789c7a44bad5fe2db05f6b5519ece);
        

        circle_marker_7fe19439637eea431f12011de3a8aaa8.bindPopup(popup_ff30df4159ae77c6e4d070a69b7570b8)
        ;

        
    
    
            var circle_marker_f3e005a07f9d68e791f360e311718044 = L.circleMarker(
                [-20.0, 30.0],
                {"bubblingMouseEvents": true, "color": "green", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "green", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1.060967094001876, "stroke": true, "weight": 3}
            ).addTo(map_dd4c0c7827ccc72813be92400204383d);
        
    
        var popup_61cd86a33db026004f59dd54278d251c = L.popup({"maxWidth": "100%"});

        
            var html_5a4a2f7949905c1aa783d36b90c6cc79 = $(`<div id="html_5a4a2f7949905c1aa783d36b90c6cc79" style="width: 100.0%; height: 100.0%;">Zimbabwe: 0.530483547000938 metric tons per capita</div>`)[0];
            popup_61cd86a33db026004f59dd54278d251c.setContent(html_5a4a2f7949905c1aa783d36b90c6cc79);
        

        circle_marker_f3e005a07f9d68e791f360e311718044.bindPopup(popup_61cd86a33db026004f59dd54278d251c)
        ;

        
    
</script>
</html>
