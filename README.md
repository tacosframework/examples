# TACOS framework examples
Example implementations of TACOS framework. Please read the definitions in the [documentation repo](https://github.com/tacosframework/documentation) for any clarifications on terms used. We’d love to grow our examples set with other implementation ideas, please contribute!

## **Lifted package (a package where a maintainer has partnered with Tidelift)**

```json
{
  "@id": "https://github.com/tacosframework/",
  "location": "document URL",
  "Signature": {"type": "sha256", "digest": "78ab8..."},
  "author": "Firstname Lastname",
  "role": "Attestor",
  "LastModifiedDateTimeUTC": "2022-03-23T05:35.37:00+04:00"
  "TACOSversion": "1.1",
  "application": "HelloWorld",
  "statements": [
   {
   "PackageName": "org.apache.samplepackage",
   "PackagePlatform": "maven",
   "PURL": "pkg:maven/org.apache.samplepackage",
   "UpstreamRepositoryURL": "https://github.com/apache/samplepackage",
   "SPDXLicenseLatestRelease": "Apache-2.0",
   "LatestStableRelease": "2.14.2",
   "ReleasesInUse": ["2.14.2, 2.14.0, 2.9.8"],
   "SBOM": [
   	{
	   "Type": "cycloneDX",
	   "URL": "https://tidelift.com/external-api/packages/maven/org.apache.samplepackage/releases/2.14.2/sbom.xml",
	   "DigitalSignatureURL": "https://tidelift.com/packages/maven/org.apache.samplepackage-latest-cycloneDX.xml.sig"
	},
	{
	   "Type": "spdx",
	   "URL": "https://tidelift.com/external-api/packages/maven/org.apache.samplepackage/releases/2.14.2/sbom.spdx",
	   "DigitalSignatureURL": "https://tidelift.com/packages/maven/org.apache.samplepackage-latest-spdx.xml.sig"
	}
   ],
   "PackageManagerMFAEnabled": "True",
   "SourceRepoMFAEnabled": "True",
   "DocumentedBuildPractices": "True",
   "KnownReleasesURL": "https://tidelift.com/packages/maven/org.apache.samplepackage/releases-map",
   "CleanReleaseAvailable": "True",
   "FixedVulnerabilities": "True",
   "DependenciesAreManaged": "True",
   "KnownVulnerabilitiesURL": "https://tidelift.com/packages/maven/org.apache.samplepackage/vulnerabilties-map",
   "PackageSecurityPolicyURL": "https://github.com/Apache/samplepackage/security/policy",
   "PackageSecurityContact": "https://tidelift.com/security",
   "SecurityResponsive": "True",
   "MultipleMaintainers": "False",
   "SuccessionPlan": "True",
   "NoBinariesInRepository": "True",
   "CodeReviewPractice": "True",
   "FuzzingPractice": "False",
   "ReleasesDigitallySigned": "False",
   "SDLCPolicyURL": "https://support.tidelift.com/hc/en-us/sections/6793135744404-Lifter-tasks",
   "SDLCEvidenceDataURL": "https://tidelift.com/packages/maven/org.apache.samplepackage/",
   "PackageStatus": {
	"status": "Active",
	"LastModifiedDateTimeUTC": "2022-03-23T05:35.37:00+04:00"
   }
   "IncomeStreams": [
   {
	"type": "Lifted",
	"EvidenceURL": "https://tidelift.com/lifted-packages",
	"LastModifiedDateTimeUTC": "2022-03-23T05:35.37:00+04:00"
   },
   {
	"type": "Variable",
	"EvidenceURL": "https://github.com/sponsors/maintainername",
	"LastModifiedDateTimeUTC": "2022-03-23T05:35.37:00+04:00"
    },
    ],
    }
 ]
}
```



## **Upstream application library built by an independent open source creator**

```json
{
  "@id": "https://github.com/tacosframework/",
  "location": "document URL",
  "signature": {"type": "sha256", "digest": "78ab8..."},
  "author": "Firstname Lastname",
  "role": "Attestor",
  "LastModifiedDateTimeUTC": "2022-03-23T05:35.37:00+04:00"
  "TACOSversion": "1.1",
  "application": "HelloWorld",
  "statements": [
   {
   "PackageName": "python-samplepackage",
   "PackagePlatform": "pypi",
   "PURL": "pkg:pypi/python-samplepackage",
   "UpstreamRepositoryURL": "https://github.com/maintainername/python-samplepackage",
   "SPDXLicenseLatestRelease": "MIT",
   "LatestStableRelease": "1.4.1",
   "ReleasesInUse": ["1.4.1"],
   "SBOM": [
   	{
	   "Type": "cycloneDX",
	   "URL": "https://tidelift.com/external-api/packages/pypi/python-samplepackage/releases/1.4.1/sbom.xml",
	   "DigitalSignatureURL": "https://tidelift.com/packages/pypi/python-samplepackage-latest-cycloneDX.xml.sig"
	},
	{
	   "Type": "spdx",
	   "URL": "https://tidelift.com/external-api/packages/pypi/python-samplepackage/releases/1.4.1/sbom.spdx",
	   "DigitalSignatureURL": "https://tidelift.com/packages/pypi/python-samplepackage-latest-spdx.xml.sig"
	}
   ],
   "PackageManagerMFAEnabled": "NOASSERTION",
   "SourceRepoMFAEnabled": "NOASSERTION",
   "DocumentedBuildPractices": "NOASSERTION",
   "KnownReleasesURL": "https://github.com/maintainername/python-samplepackage/tags",
   "CleanReleaseAvailable": "False",
   "FixedVulnerabilities": "False",
   "DependenciesAreManaged": "False",
   "KnownVulnerabilitiesURL": "https://nvd.nist.gov/vuln/detail/CVE-2023-XXXXX",
   "PackageSecurityPolicyURL": "https://github.com/maintainername/python-samplepackage/security",
   "PackageSecurityContact": "https://github.com/maintainername/python-samplepackage/security",
   "SecurityResponsive": "True",
   "MultipleMaintainers": "True",
   "SuccessionPlan": "NOASSERTION",
   "NoBinariesInRepository": "NOASSERTION",
   "CodeReviewPractice": "NOASSERTION",
   "FuzzingPractice": "NOASSERTION",
   "ReleasesDigitallySigned": "False",
   "SDLCPolicyURL": "NOASSERTION",
   "SDLCEvidenceDataURL": "NOASSERTION",
   "PackageStatus": {
	"status": "Inactive",
	"LastModifiedDateTimeUTC": "2022-03-23T05:35.37:00+04:00"
   }
   "IncomeStreams": ["NOASSERTION"],
   }
 ]
}
```


## **Upstream application library supported by a vendor**
```json
{
  "@id": "https://github.com/tacosframework/",
  "location": "document URL",
  "signature": {"type": "sha256", "digest": "78ab8..."},
  "author": "Firstname Lastname",
  "role": "Attestor",
  "LastModifiedDateTimeUTC": "2022-03-23T05:35.37:00+04:00"
  "TACOSversion": "1.1",
  "application": "HelloWorld",
  "statements": [
   {
   "PackageName": "org.springframework.boot:spring-boot",
   "PackagePlatform": "maven",
   "PURL": "pkg:maven/org.springframework.boot:spring-boot",
   "UpstreamRepositoryURL": "https://repo1.maven.org/maven2/org/springframework/boot/spring-boot/",
   "SPDXLicenseLatestRelease": "Apache-2.0",
   "LatestStableRelease": "3.0.5",
   "ReleasesInUse": ["2.2.1.RELEASE, 2.7.10, 2.7.8, 2.7.7"],
   "SBOM": [
   	{
	   "Type": "cycloneDX",
	   "URL": "https://tidelift.com/external-api/packages/maven/org.springframework.boot/releases/3.0.5/sbom.xml",
	   "DigitalSignatureURL": "https://tidelift.com/packages/maven/org.springframework.boot:spring-boot-latest-cycloneDX.xml.sig"
	},
	{
	   "Type": "spdx",
	   "URL": "https://tidelift.com/external-api/packages/maven/org.springframework.boot/releases/3.0.5/sbom.spdx",
	   "DigitalSignatureURL": "https://tidelift.com/packages/maven/org.springframework.boot:spring-boot-latest-spdx.xml.sig"
	}
   ],
   "PackageManagerMFAEnabled": "NOASSERTION",
   "SourceRepoMFAEnabled": "NOASSERTION",
   "DocumentedBuildPractices": "NOASSERTION",
   "KnownReleasesURL": "https://tidelift.com/packages/maven/org.springframework.boot:spring-boot/releases-map",
   "CleanReleaseAvailable": "True",
   "FixedVulnerabilities": "False",
   "DependenciesAreManaged": "False",
   "KnownVulnerabilitiesURL": "https://tidelift.com/packages/maven/org.springframework.boot:spring-boot/vulnerabilties-map",
   "PackageSecurityPolicyURL": "https://www.vmware.com/support/policies/security_response.html",
   "PackageSecurityContact": "security@vmware.com",
   "SecurityResponsive": "True",
   "MultipleMaintainers": "True",
   "SuccessionPlan": "True",
   "NoBinariesInRepository": "NOASSERTION",
   "CodeReviewPractice": "NOASSERTION",
   "FuzzingPractice": "NOASSERTION",
   "ReleasesDigitallySigned": "NOASSERTION",
   "SDLCPolicyURL": "https://www.vmware.com/content/dam/digitalmarketing/vmware/en/pdf/support/vmware-external-vulnerability-response-and-remediation-policy.pdf",
   "SDLCEvidenceDataURL": "https://spring.io/security/",
   "PackageStatus": {
	"status": "Active",
	"LastModifiedDateTimeUTC": "2022-03-23T05:35.37:00+04:00"
   }
   "IncomeStreams":  [
   {
	"type": "Corporate",
	"EvidenceURL": "https://spring.io/",
	"LastModifiedDateTimeUTC": "2022-03-23T05:35.37:00+04:00"
   },
   ],
   }
 ]
}
```
