{
  "data": {
    "id": "902675",
    "type": "shipments",
    "attributes": {
      "status": "WAITING",
      "created_at": "2018-12-18T15:00:21.892-06:00",
      "updated_at": "2018-12-18T15:00:21.892-06:00"
    },
    "relationships": {
      "parcel": {
        "data": {
          "id": "773773",
          "type": "parcels"
        }
      },
      "rates": {
        "data": [
          {
            "id": "7146454",
            "type": "rates"
          },
          {
            "id": "7146455",
            "type": "rates"
          },
          {
            "id": "7146456",
            "type": "rates"
          },
          {
            "id": "7146457",
            "type": "rates"
          },
          {
            "id": "7146458",
            "type": "rates"
          }
        ]
      },
      "address_to": {
        "data": {
          "id": "2901622",
          "type": "addresses"
        }
      },
      "address_from": {
        "data": {
          "id": "2901621",
          "type": "addresses"
        }
      },
      "label": {
        "data": null
      }
    }
  },
  "included": [
    {
      "id": "773773",
      "type": "parcels",
      "attributes": {
        "length": "10.0",
        "height": "10.0",
        "width": "10.0",
        "weight": "3.0",
        "mass_unit": "KG",
        "distance_unit": "CM"
      }
    },
    {
      "id": "7146454",
      "type": "rates",
      "attributes": {
        "created_at": "2018-12-18T15:00:22.141-06:00",
        "updated_at": "2018-12-18T15:00:22.141-06:00",
        "amount_local": "149.0",
        "currency_local": "MXN",
        "provider": "FEDEX",
        "service_level_name": "Fedex Express Saver",
        "service_level_code": "FEDEX_EXPRESS_SAVER",
        "service_level_terms": null,
        "days": 5,
        "duration_terms": null,
        "zone": null,
        "arrives_by": null,
        "out_of_area": true,
        "out_of_area_pricing": "145.00",
        "total_pricing": "294.0"
      }
    },
    {
      "id": "7146455",
      "type": "rates",
      "attributes": {
        "created_at": "2018-12-18T15:00:22.150-06:00",
        "updated_at": "2018-12-18T15:00:22.150-06:00",
        "amount_local": "205.0",
        "currency_local": "MXN",
        "provider": "FEDEX",
        "service_level_name": "Standard Overnight",
        "service_level_code": "STANDARD_OVERNIGHT",
        "service_level_terms": null,
        "days": 2,
        "duration_terms": null,
        "zone": null,
        "arrives_by": null,
        "out_of_area": true,
        "out_of_area_pricing": "145.00",
        "total_pricing": "350.0"
      }
    },
    {
      "id": "7146456",
      "type": "rates",
      "attributes": {
        "created_at": "2018-12-18T15:00:22.380-06:00",
        "updated_at": "2018-12-18T15:00:22.380-06:00",
        "amount_local": "180.0",
        "currency_local": "MXN",
        "provider": "DHL",
        "service_level_name": "DHL Terrestre",
        "service_level_code": "STANDARD",
        "service_level_terms": null,
        "days": 5,
        "duration_terms": null,
        "zone": null,
        "arrives_by": null,
        "out_of_area": true,
        "out_of_area_pricing": "145.00",
        "total_pricing": "325.0"
      }
    },
    {
      "id": "7146457",
      "type": "rates",
      "attributes": {
        "created_at": "2018-12-18T15:00:22.389-06:00",
        "updated_at": "2018-12-18T15:00:22.389-06:00",
        "amount_local": "204.0",
        "currency_local": "MXN",
        "provider": "DHL",
        "service_level_name": "DHL Express",
        "service_level_code": "EXPRESS",
        "service_level_terms": null,
        "days": 2,
        "duration_terms": null,
        "zone": null,
        "arrives_by": null,
        "out_of_area": true,
        "out_of_area_pricing": "145.00",
        "total_pricing": "349.0"
      }
    },
    {
      "id": "7146458",
      "type": "rates",
      "attributes": {
        "created_at": "2018-12-18T15:00:22.418-06:00",
        "updated_at": "2018-12-18T15:00:22.418-06:00",
        "amount_local": "119.0",
        "currency_local": "MXN",
        "provider": "CARSSA",
        "service_level_name": "Nacional",
        "service_level_code": "NACIONAL",
        "service_level_terms": null,
        "days": 5,
        "duration_terms": null,
        "zone": null,
        "arrives_by": null,
        "out_of_area": false,
        "out_of_area_pricing": "0.0",
        "total_pricing": "119.0"
      }
    },
    {
      "id": "2901622",
      "type": "addresses",
      "attributes": {
        "name": "Jorge Fern??ndez",
        "company": "-",
        "address1": "Av. L??zaro C??rdenas #234",
        "address2": "Americana",
        "city": "Guadalajara",
        "province": "Jalisco",
        "zip": "23312",
        "country": "MX",
        "phone": "5555555555",
        "email": "ejemplo@skydropx.com",
        "created_at": "2018-12-18T15:00:21.887-06:00",
        "updated_at": "2018-12-18T15:00:21.887-06:00"
      }
    },
    {
      "id": "2901621",
      "type": "addresses",
      "attributes": {
        "name": "Jose Fernando",
        "company": "skydropx",
        "address1": "Av. Principal #234",
        "address2": "Centro",
        "city": "Guadalajara",
        "province": "Jalisco",
        "zip": "02900",
        "country": "MX",
        "phone": "5555555555",
        "email": "skydropx@email.com",
        "created_at": "2018-12-18T15:00:21.874-06:00",
        "updated_at": "2018-12-18T15:00:21.874-06:00"
      }
    }
  ]
}
