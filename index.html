<!DOCTYPE html>
<html>

<head>
    <style>
        /*  <span class="metadata-marker" style="display: none;" data-region_tag="css"></span>       Set the size of the div element that contains the map */
        #map {
            height: 400px;
            /* The height is 400 pixels */
            width: 100%;
            /* The width is the width of the web page */
        }
    </style>
    <script>
        var map;
        var InforObj = [];
        var centerCords = {
            lat: -1.605328,
            lng: 117.451067
        };
        var markersOnMap = [{
                placeName: "Yogyakarta",
                LatLng: [{
                    lat: -7.797068,
                    lng: 110.370529
                }]
            },
            {
                placeName: "Sleman",
                LatLng: [{
                    lat: -7.71556,
                    lng: 110.35556
                }]
            },
            {
                placeName: "Wates",
                LatLng: [{
                    lat: -7.6450,
                    lng: 110.0269
                }]
            },
            {
                placeName: "Gunung Kidul",
                LatLng: [{
                    lat: -7.9833,
                    lng: 110.6167
                }]
            },
            {
                placeName: "Bantul",
                LatLng: [{
                    lat: -7.840243,
                    lng: 110.408333
                }]
            }
        ];

        window.onload = function () {
            initMap();
        };

        function addMarkerInfo() {
            for (var i = 0; i < markersOnMap.length; i++) {
                var contentString = '<div id="content"><h1>' + markersOnMap[i].placeName +
                    '</h1><p>Test googlemap API</p></div>';

                const marker = new google.maps.Marker({
                    position: markersOnMap[i].LatLng[0],
                    map: map
                });

                const infowindow = new google.maps.InfoWindow({
                    content: contentString,
                    maxWidth: 200
                });

                marker.addListener('click', function () {
                    closeOtherInfo();
                    infowindow.open(marker.get('map'), marker);
                    InforObj[0] = infowindow;
                });
                // marker.addListener('mouseover', function () {
                //     closeOtherInfo();
                //     infowindow.open(marker.get('map'), marker);
                //     InforObj[0] = infowindow;
                // });
                // marker.addListener('mouseout', function () {
                //     closeOtherInfo();
                //     infowindow.close();
                //     InforObj[0] = infowindow;
                // });
            }
        }

        function closeOtherInfo() {
            if (InforObj.length > 0) {
                /* detach the info-window from the marker ... undocumented in the API docs */
                InforObj[0].set("marker", null);
                /* and close it */
                InforObj[0].close();
                /* blank the array */
                InforObj.length = 0;
            }
        }

        function initMap() {
            map = new google.maps.Map(document.getElementById('map'), {
                zoom: 4,
                center: centerCords
            });
            addMarkerInfo();
        }
    </script>
</head>

<body>
    <h3>My Google Maps Demo</h3>
    <!--The div element for the map -->
    <div id="map"></div>

    <script src="https://maps.googleapis.com/maps/api/js?key=AIzaSyBs84T-ieA-SE4rYxlZmppOu9xQKlwj4l0"></script>

</body>

</html>
