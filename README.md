# TACOS framework examples
Example implementations of TACOS framework. Please read the definitions in the [documentation repo](https://github.com/tacosframework/documentation) for any clarifications on terms used. We’d love to grow our examples set with other implementation ideas, please contribute!

## **Lifted package (a package where a maintainer has partnered with Tidelift)**

```json
{
  "@context": "domain/namespace",
  "@id": "document URL",
  "signature": {"type": "sha256", "digest": "78ab8..."},
  "author": "Firstname Lastname",
  "role": "Attestor",
  "timestamp": "2022-03-23T05:35.37:00+04:00",
  "TACOSversion": "1",
  "application": "HelloWorld",
  "statements": [
   {
   "PackageName": "org.apache.samplepackage",
   "PackagePlatform": "maven",
   "PURL": "pkg:maven/org.apache.samplepackage",
   "UpstreamRepositoryURL": "https://github.com/apache/samplepackage",
   "SPDXLicenseLatestRelease": "Apache-2.0",
   "LatestRelease": "2.14.2",
   "ReleasesInUse": ["2.14.2, 2.14.0, 2.9.8"],
   "SBOM": {
	   "type": "cycloneDX",
	   "version": "1.2",
	   "format": "XML",
	   "DigitalSignatureURL": "https://tidelift.com/packages/maven/org.apache.samplepackage-latest-cycloneDX.xml.sig",
	   "URL": "https://tidelift.com/packages/maven/org.apache.samplepackage-latest-cycloneDX.xml"
	},
	"PackageManager2FAEnabled": "True",
	"SourceRepo2FAEnabled": "True",
	"KnownReleasesURL": "https://tidelift.com/packages/maven/org.apache.samplepackage/releases-map",
	"CleanReleaseAvailable": "True",
	"KnownVulnerabilities": "False",
	"KnownVulnerabilitiesInDependencies": "False",
	"KnownVulnerabilitiesURL": "https://tidelift.com/packages/maven/org.apache.samplepackage/vulnerabilties-map",
	"PackageSecurityPolicyURL": "https://github.com/Apache/samplepackage/security/policy",
	"PackageSecurityContact": "https://tidelift.com/security",
	"BinariesInRepository": "False",
	"CodeReviewPractice": "True",
	"FuzzingPractice": "False",
	"ReproducibleBuilds": "False",
	"ReleasesDigitallySigned": "False",
	"SDLCPolicyURL": "https://support.tidelift.com/hc/en-us/sections/6793135744404-Lifter-tasks",
	"SDLCEvidenceDataURL": "https://tidelift.com/packages/maven/org.apache.samplepackage/",
	"PackageStatus": {
		"status": "active",
		"LastModifiedDateTimeUTC": "2023-01-21T15:05:00"
	}
	"IncomeStreams": [
	{
		"type": "lifted",
		"EvidenceURL": "https://tidelift.com/lifted-packages",
		"LastModifiedDateTimeUTC": "2022-01-21T15:05:00"
	},
	{
	"type": "variable",
	"EvidenceURL": "https://github.com/sponsors/maintainername",
	"LastModifiedDateTimeUTC": "2022-01-21T15:05:00"
	},
	],
	"LastModifiedDateTimeUTC": "2023-01-21T15:05:00"
	}
 ]
}
```



## **Upstream application library built by an independent open source creator**




## **Upstream application library supported by a vendor**
