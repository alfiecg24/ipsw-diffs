## SleepDaemon

> `/System/Library/PrivateFrameworks/SleepDaemon.framework/SleepDaemon`

```diff

-5200.1.7.0.0
-  __TEXT.__text: 0x780f0
-  __TEXT.__auth_stubs: 0xc20
-  __TEXT.__objc_methlist: 0x7214
+5200.1.9.1.2
+  __TEXT.__text: 0x7a584
+  __TEXT.__auth_stubs: 0xc30
+  __TEXT.__objc_methlist: 0x73b4
   __TEXT.__const: 0x1c8
-  __TEXT.__cstring: 0x2a77
-  __TEXT.__oslogstring: 0xb6e5
-  __TEXT.__gcc_except_tab: 0x11c4
-  __TEXT.__unwind_info: 0x2180
-  __TEXT.__objc_classname: 0x1efd
-  __TEXT.__objc_methname: 0x10e85
-  __TEXT.__objc_methtype: 0x3570
-  __TEXT.__objc_stubs: 0xcc20
-  __DATA_CONST.__got: 0xa00
-  __DATA_CONST.__const: 0x23e0
-  __DATA_CONST.__objc_classlist: 0x530
+  __TEXT.__cstring: 0x2afb
+  __TEXT.__oslogstring: 0xb855
+  __TEXT.__gcc_except_tab: 0x127c
+  __TEXT.__unwind_info: 0x21d8
+  __TEXT.__objc_classname: 0x1f1e
+  __TEXT.__objc_methname: 0x11a16
+  __TEXT.__objc_methtype: 0x360b
+  __TEXT.__objc_stubs: 0xd520
+  __DATA_CONST.__got: 0xa78
+  __DATA_CONST.__const: 0x2450
+  __DATA_CONST.__objc_classlist: 0x538
   __DATA_CONST.__objc_catlist: 0x58
   __DATA_CONST.__objc_protolist: 0x310
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x38d8
+  __DATA_CONST.__objc_selrefs: 0x3b20
   __DATA_CONST.__objc_protorefs: 0x18
-  __DATA_CONST.__objc_superrefs: 0x350
-  __AUTH_CONST.__auth_got: 0x620
-  __AUTH_CONST.__const: 0xce0
-  __AUTH_CONST.__cfstring: 0x1e60
-  __AUTH_CONST.__objc_const: 0x123a0
+  __DATA_CONST.__objc_superrefs: 0x358
+  __AUTH_CONST.__auth_got: 0x628
+  __AUTH_CONST.__const: 0xd00
+  __AUTH_CONST.__cfstring: 0x1ec0
+  __AUTH_CONST.__objc_const: 0x12640
   __AUTH_CONST.__objc_intobj: 0x60
-  __AUTH.__objc_data: 0xc80
-  __DATA.__objc_ivar: 0x570
+  __AUTH.__objc_data: 0xcd0
+  __DATA.__objc_ivar: 0x5a0
   __DATA.__data: 0x24d0
   __DATA_DIRTY.__objc_ivar: 0xd0
   __DATA_DIRTY.__objc_data: 0x2760

   - /System/Library/PrivateFrameworks/ToneLibrary.framework/ToneLibrary
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 2929
-  Symbols:   3555
-  CStrings:  4482
+  Functions: 2968
+  Symbols:   3611
+  CStrings:  4590
 
Symbols:
+ _HKSampleSortIdentifierStartDate
+ _OBJC_CLASS_$_HKSampleQuery
+ _HKCategoryTypeIdentifierSleepApneaEvent
+ _HKSHBreathingDisturbanceAnalysisSchedulerLastSuccessfulAnalysisAttemptDateKey
+ _OBJC_CLASS_$_HKQueryDescriptor
+ _OBJC_METACLASS_$_HDSPSleepApneaAnalyticsBuilder
+ _HKSHBreathingDisturbanceKeyValueDomainName
+ _HKFeatureIdentifierSleepApneaNotifications
+ _OBJC_CLASS_$_HKFeatureStatusManager
+ _OBJC_CLASS_$_NSSortDescriptor
+ _HKQuantityTypeIdentifierAppleSleepingBreathingDisturbances
+ _OBJC_CLASS_$_HKSampleType
+ _OBJC_CLASS_$_NSPredicate
+ _HKFeatureAvailabilityRequirementIdentifierFeatureIsOn
+ _OBJC_CLASS_$_HDSPSleepApneaAnalyticsBuilder
+ _HKAppleSleepingBreathingDisturbancesMinimumQuantityForClassification
+ _HKFeatureAvailabilityContextUsage
CStrings:
+ "now"
+ "_weeksSinceOnboardedBD"
+ "_value"
+ "_breathingDisturbanceSamples"
+ "_numSleepDaysWithMultipleBDsInTheLast30Days"
+ "_numBDValuesInPastNight:"
+ "v72@0:8@16@24@32@40{?=qq}48@64"
+ "onboardingRecord"
+ "setNumSleepSessionsWithBDsOverThresholdLast30Days:"
+ "initWithEnvironment:daySummaries:breathingDisturbanceSamples:sleepApneaEventSamples:sleepApneaFeatureStatus:morningIndexRange:"
+ "setNumDaysSinceLastBDNotification:"
+ "setBDOnboardingCountryCode:"
+ "_breathingDisturbanceSamplesInPastNight"
+ "@72@0:8@16@24@32@40@48{?=qq}56"
+ "valueForKeyPath:"
+ "_numSleepSessionsWithBDsOverThresholdLast30Days"
+ "isRequirementSatisfiedWithIdentifier:"
+ "[%!{(MISSING)public}@] Error while querying for breathing disturbance samples: %!@(MISSING)"
+ "T@\"NSArray\",R,N,V_sleepApneaEventSamples"
+ "_sleepApneaEventSamplesInPastNights:"
+ "countUnit"
+ "_numDaysSinceLastAnalysis"
+ "quantity"
+ "_numSleepDaysWithBDsOverThresholdLast30Days"
+ "T@\"HDSPSleepApneaAnalyticsBuilder\",R,N,V_sleepApneaAnalyticsBuilder"
+ "T@\"NSArray\",R,N,V_breathingDisturbanceSamples"
+ "[%!{(MISSING)public}@] Queries failed with error: %!{(MISSING)public}@"
+ "_maximumBDValueInPast30Days"
+ "featureStatusWithError:"
+ "@\"HDSPSleepApneaAnalyticsBuilder\""
+ "initWithCategory:domainName:healthStore:"
+ "_sleepApneaFeatureStatus"
+ "earliestDateOfAnyOnboardingCompletion"
+ "_numBDValuesInPast30Days"
+ "_maxTimeBetweenBDSessionsPastNight:"
+ "[%!{(MISSING)public}@] Building daily analytics report from %!{(MISSING)public}lu bd samples"
+ "setMaxBDValueInPast30Days:"
+ "_numDaysSinceLastBDNotification"
+ "@max.doubleValue"
+ "setNumBDNotificationsInPast30Nights:"
+ "_numBDNotifications:"
+ "gregorianCalendar"
+ "_gregorianCalendar"
+ "updateDailyReportWithSleepApneaAnalytics:"
+ "setAreHealthNotificationsAuthorized:"
+ "setMinTimeBetweenBDSessionsPastNight:"
+ "F"
+ "_calculateBreathingDisturbanceValueDependentMetrics"
+ "[%!{(MISSING)public}@] Queries succeeded"
+ "setNumBDValuesInPastNight:"
+ "d"
+ "setWeeksSinceOnboardedBD:"
+ "_creationDate"
+ "initWithSampleType:predicate:"
+ "authorizationStatus"
+ "initWithCapacity:"
+ "_maxBDValueInPast30Days"
+ "setIsOnboardedBD:"
+ "@24@0:8q16"
+ "sleepApneaFeatureStatus"
+ "@\"NSCalendar\""
+ "@\"NSDate\"8@?0"
+ "hk_predicateForSamplesInDayIndexRange:"
+ "setNumBDNotificationsInPastNight:"
+ "initWithQueryDescriptors:limit:sortDescriptors:resultsHandler:"
+ "_numSleepDaysWithMultipleBDsInLast30Days"
+ "setNumBDValuesInPast30Days:"
+ "T@\"HKFeatureStatus\",R,N,V_sleepApneaFeatureStatus"
+ "setNumDaysSinceLastAnalysis:"
+ "breathingDisturbanceSamples"
+ "_sleepApneaAnalyticsBuilder"
+ "_processQueryResultsWithSummaries:breathingDisturbanceSamples:sleepApneaEventSamples:sleepApneaFeatureStatus:queryRange:error:"
+ "_areHealthNotificationsAuthorized"
+ "initWithBreathingDisturbanceSamples:sleepApneaEventSamples:sleepApneaFeatureStatus:morningIndexRange:gregorianCalendar:dateOfLastAnalysis:currentDateProvider:"
+ "_dateOfLastAnalysis"
+ "setMaxTimeBetweenBDSessionsPastNight:"
+ "setNumBDNotificationsInPast180Nights:"
+ "@avg.doubleValue"
+ "_isEnabledBD"
+ "v32@?0@\"HKSampleQuery\"8@\"NSArray\"16@\"NSError\"24"
+ "@\"HKFeatureStatus\""
+ "notificationSettings"
+ "sortDescriptorWithKey:ascending:"
+ "_onboardedCountryCode"
+ "onboardedCountryCodesForOnboardingState"
+ "@min.doubleValue"
+ "dateOfLastAnalysis"
+ "T@\"NSCalendar\",R,N,V_gregorianCalendar"
+ "_typeWithIdentifier:"
+ "B16@?0@\"HKSample\"8"
+ "setMeanTimeBetweenBDSessionsPastNight:"
+ "sleepApneaAnalyticsBuilder"
+ "_isOnboardedBD"
+ "HDSPSleepApneaAnalyticsBuilder"
+ "_sleepApneaEventSamples"
+ "T@\"NSDate\",R,C,N,V_dateOfLastAnalysis"
+ "_meanTimeBetweenBDSessionsPastNight:"
+ "initWithFeatureIdentifier:healthStore:"
+ "@80@0:8@16@24@32{?=qq}40@56@64@?72"
+ "isOnboardingRecordPresent"
+ "setNumSleepDaysWithMultipleBDinPast30Days:"
+ "[%!{(MISSING)public}@] Beginning bd queries"
+ "nebula"
+ "[%!{(MISSING)public}@] Error while querying fetching apnea feature status: %!@(MISSING)"
+ "_timesBetweenBDSessions:"
+ "_dateOfLastSuccessfulBreathingDisturbanceAnalysis"
+ "setNumSleepDaysWithBDsOverThresholdLast30Days:"
+ "_minTimeBetweenBDSessionsPastNight:"
+ "dateForKey:error:"
+ "sleepApneaEventSamples"
+ "[%!{(MISSING)public}@] Error while querying for sleep apnea event samples: %!@(MISSING)"
- "v48@0:8@16{?=qq}24@40"
- "[%!{(MISSING)public}@] Query succeeded"
- "_processQueryResultsWithSummaries:queryRange:error:"

```
