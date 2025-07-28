[
  {
    "AccountId": "462397577549",
    "Arn": "arn:aws:guardduty:eu-north-1:462397577549:detector/f2cc276b7772d140efd9cd46c0d2e8cf/finding/b4cc276ec295e896933a5089da8502a3",
    "CreatedAt": "2025-07-28T02:29:57.163Z",
    "Description": "The API DescribeAlarms was invoked using root credentials from IP address 14.96.13.220.",
    "Id": "b4cc276ec295e896933a5089da8502a3",
    "Partition": "aws",
    "Region": "eu-north-1",
    "Resource": {
      "AccessKeyDetails": {
        "AccessKeyId": "ASIAWXKILDFG7EAZW4TS",
        "PrincipalId": "462397577549",
        "UserName": "Root",
        "UserType": "Root"
      },
      "ResourceType": "AccessKey"
    },
    "SchemaVersion": "2.0",
    "Service": {
      "Action": {
        "ActionType": "AWS_API_CALL",
        "AwsApiCallAction": {
          "Api": "DescribeAlarms",
          "CallerType": "Remote IP",
          "RemoteIpDetails": {
            "City": {
              "CityName": "Chennai"
            },
            "Country": {
              "CountryName": "India"
            },
            "GeoLocation": {
              "Lat": 13.0895,
              "Lon": 80.2739
            },
            "IpAddressV4": "14.96.13.220",
            "Organization": {
              "Asn": "45820",
              "AsnOrg": "Tata Teleservices ISP AS",
              "Isp": "Tata Teleservices ISP",
              "Org": "Tata Teleservices ISP"
            }
          },
          "ServiceName": "monitoring.amazonaws.com",
          "AffectedResources": {}
        }
      },
      "Archived": false,
      "Count": 110,
      "DetectorId": "f2cc276b7772d140efd9cd46c0d2e8cf",
      "EventFirstSeen": "2025-07-28T02:22:46.000Z",
      "EventLastSeen": "2025-07-28T02:26:07.000Z",
      "ResourceRole": "TARGET",
      "ServiceName": "guardduty",
      "AdditionalInfo": {
        "Value": "{}",
        "Type": "default"
      }
    },
    "Severity": 2,
    "Title": "The API DescribeAlarms was invoked using root credentials.",
    "Type": "Policy:IAMUser/RootCredentialUsage",
    "UpdatedAt": "2025-07-28T02:32:07.839Z"
  }
]
