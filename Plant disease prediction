<?xml version="1.0" encoding="utf-8" ?>
<manifest xmlns:android="http://schemas.android.com/apk/res/android" android:compileSdkVersion="35" android:compileSdkVersionCodename="15" android:installLocation="internalOnly" android:versionCode="368" android:versionName="4.9.1" package="com.peat.GartenBank" platformBuildVersionCode="35" platformBuildVersionName="15">
	<uses-sdk android:minSdkVersion="23" android:targetSdkVersion="34" />
	<uses-feature android:name="android.hardware.camera" android:required="true" />
	<uses-feature android:name="android.hardware.camera.autofocus" android:required="true" />
	<uses-permission android:name="android.permission.ACCESS_COARSE_LOCATION" />
	<uses-permission android:name="android.permission.CAMERA" />
	<uses-permission android:maxSdkVersion="32" android:name="android.permission.WRITE_EXTERNAL_STORAGE" />
	<uses-permission android:maxSdkVersion="32" android:name="android.permission.READ_EXTERNAL_STORAGE" />
	<uses-permission android:name="android.permission.INTERNET" />
	<uses-permission android:name="android.permission.ACCESS_NETWORK_STATE" />
	<uses-permission android:name="android.permission.ACCESS_FINE_LOCATION" />
	<uses-permission android:name="android.permission.VIBRATE" />
	<queries>
		<package android:name="com.whatsapp" />
		<package android:name="com.facebook.katana" />
		<package android:name="com.facebook.lite" />
		<package android:name="com.twitter.android" />
		<package android:name="org.telegram.messenger" />
		<intent>
			<action android:name="android.intent.action.PICK" />
			<data android:mimeType="image/*" />
		</intent>
		<intent>
			<action android:name="android.media.action.IMAGE_CAPTURE" />
		</intent>
		<intent>
			<action android:name="android.intent.action.MAIN" />
			<category android:name="android.intent.category.APP_EMAIL" />
		</intent>
		<intent>
			<action android:name="android.intent.action.VIEW" />
			<category android:name="android.intent.category.BROWSABLE" />
			<data android:scheme="https" />
		</intent>
		<intent>
			<action android:name="android.support.customtabs.action.CustomTabsService" />
		</intent>
		<intent>
			<action android:name="android.speech.RecognitionService" />
		</intent>
		<intent>
			<action android:name="android.intent.action.TTS_SERVICE" />
		</intent>
		<package android:name="com.google.android.apps.maps" />
		<intent>
			<action android:name="com.appsflyer.referrer.INSTALL_PROVIDER" />
		</intent>
		<package android:name="com.instagram.android" />
		<package android:name="com.samsung.android.mapsagent" />
	</queries>
	<uses-permission android:name="android.permission.POST_NOTIFICATIONS" />
	<uses-permission android:name="android.permission.RECORD_AUDIO" />
	<uses-feature android:glEsVersion="0x20000" android:required="true" />
	<uses-permission android:name="android.permission.WAKE_LOCK" />
	<uses-permission android:name="android.permission.RECEIVE_BOOT_COMPLETED" />
	<uses-permission android:name="android.permission.FOREGROUND_SERVICE" />
	<uses-permission android:name="com.google.android.c2dm.permission.RECEIVE" />
	<uses-permission android:name="com.peat.GartenBank.DYNAMIC_RECEIVER_NOT_EXPORTED_PERMISSION" />
	<uses-permission android:name="com.google.android.finsky.permission.BIND_GET_INSTALL_REFERRER_SERVICE" />
	<uses-permission android:name="com.google.android.gms.permission.AD_ID" />
	<uses-permission android:name="android.permission.ACCESS_ADSERVICES_ATTRIBUTION" />
	<uses-permission android:name="android.permission.ACCESS_ADSERVICES_AD_ID" />
	<uses-permission android:name="android.permission.ACCESS_ADSERVICES_CUSTOM_AUDIENCE" />
	<permission android:name="com.peat.GartenBank.DYNAMIC_RECEIVER_NOT_EXPORTED_PERMISSION" android:protectionLevel="signature" />
	<uses-permission android:name="com.google.android.providers.gsf.permission.READ_GSERVICES" />
	<uses-permission android:name="com.samsung.android.mapsagent.permission.READ_APP_INFO" />
	<uses-permission android:name="com.huawei.appmarket.service.commondata.permission.GET_COMMON_DATA" />
	<uses-permission android:name="android.permission.QUERY_ALL_PACKAGES" />
	<application android:allowBackup="false" android:appComponentFactory="androidx.core.app.CoreComponentFactory" android:dataExtractionRules="@xml/appsflyer_data_extraction_rules" android:enableOnBackInvokedCallback="false" android:fullBackupContent="@xml/appsflyer_backup_rules" android:icon="@mipmap/ic_launcher" android:label="@string/app_name" android:localeConfig="@xml/locales_config" android:name="com.mma.speedremoveads.RMApplication" android:roundIcon="@mipmap/ic_launcher_round" android:supportsRtl="true" android:theme="@style/Base.Theme">
		<meta-data android:name="com.google.android.gms.version" android:value="@integer/google_play_services_version" />
		<meta-data android:name="firebase_performance_collection_deactivated" android:value="false" />
		<meta-data android:name="com.facebook.sdk.ApplicationId" android:value="@string/facebook_app_id_production" />
		<meta-data android:name="com.facebook.sdk.ClientToken" android:value="@string/facebook_client_token_production" />
		<meta-data android:name="com.facebook.sdk.AutoLogAppEventsEnabled" android:value="false" />
		<meta-data android:name="com.facebook.sdk.AdvertiserIDCollectionEnabled" android:value="false" />
		<meta-data android:name="firebase_analytics_collection_enabled" android:value="false" />
		<meta-data android:name="google_analytics_adid_collection_enabled" android:value="true" />
		<meta-data android:name="firebase_crashlytics_collection_enabled" android:value="false" />
		<service android:enabled="false" android:exported="false" android:name="androidx.appcompat.app.AppLocalesMetadataHolderService">
			<meta-data android:name="autoStoreLocales" android:value="false" />
		</service>
		<activity android:exported="true" android:name="com.rob.plantix.base.activities.LaunchActivity" android:screenOrientation="portrait" android:theme="@style/SplashTheme">
			<intent-filter>
				<action android:name="android.intent.action.MAIN" />
				<category android:name="android.intent.category.LAUNCHER" />
			</intent-filter>
			<intent-filter android:autoVerify="true">
				<action android:name="android.intent.action.VIEW" />
				<category android:name="android.intent.category.DEFAULT" />
				<category android:name="android.intent.category.BROWSABLE" />
				<data android:scheme="http" />
				<data android:scheme="https" />
				<data android:host="www.plantix.net" />
				<data android:host="plantix.net" />
				<data android:pathPattern="/.." />
				<data android:pathPattern="/../" />
				<data android:pathPattern="/../share/welcome/.*" />
				<data android:pathPattern="/share/.*" />
				<data android:pathPattern="/../library/plant-diseases/.*" />
				<data android:pathPrefix="/plant-disease" />
				<data android:pathPrefix="/web_link" />
				<data android:pathPrefix="/campaign" />
				<data android:pathPattern="/../library/treatment/.*" />
				<data android:pathPattern="/../advisory/event/.*" />
				<data android:pathPrefix="/select_your_retailer" />
				<data android:pathPattern="/community/../post/.*" />
			</intent-filter>
			<intent-filter android:autoVerify="true">
				<action android:name="android.intent.action.VIEW" />
				<category android:name="android.intent.category.DEFAULT" />
				<category android:name="android.intent.category.BROWSABLE" />
				<data android:scheme="http" />
				<data android:scheme="https" />
				<data android:host="shop.plantix.net" />
				<data android:pathPattern="/.." />
				<data android:pathPattern="/../" />
				<data android:pathPattern="/../stores/.*/.*" />
				<data android:pathPattern="/../products/.*" />
			</intent-filter>
			<intent-filter android:autoVerify="true">
				<action android:name="android.intent.action.VIEW" />
				<category android:name="android.intent.category.DEFAULT" />
				<category android:name="android.intent.category.BROWSABLE" />
				<data android:host="plantix.onelink.me" android:scheme="https" />
			</intent-filter>
		</activity>
		<activity-alias android:enabled="false" android:exported="true" android:name="com.rob.plantix.defaultAppMimeTextPlain" android:targetActivity="com.rob.plantix.base.activities.LaunchActivity">
			<intent-filter>
				<action android:name="android.intent.action.SEND" />
				<category android:name="android.intent.category.DEFAULT" />
				<data android:mimeType="text/plain" />
			</intent-filter>
		</activity-alias>
		<activity android:exported="true" android:label="@string/app_name" android:launchMode="singleTask" android:name="com.rob.plantix.base.activities.MainActivity" android:screenOrientation="portrait" android:windowSoftInputMode="adjustPan" />
		<meta-data android:name="com.google.firebase.messaging.default_notification_icon" android:resource="@drawable/notification_icon" />
		<meta-data android:name="com.google.firebase.messaging.default_notification_color" android:resource="@color/colorPrimary" />
		<meta-data android:name="com.google.android.geo.API_KEY" android:value="@string/google_api_key" />
		<service android:exported="true" android:name="com.rob.plantix.fcm.FirebaseMessageService">
			<intent-filter>
				<action android:name="com.google.firebase.MESSAGING_EVENT" />
			</intent-filter>
		</service>
		<activity android:name="com.google.android.gms.oss.licenses.OssLicensesActivity" android:screenOrientation="portrait" android:theme="@style/OssLicencesTheme" />
		<activity android:label="@string/oss_license_title" android:name="com.google.android.gms.oss.licenses.OssLicensesMenuActivity" android:screenOrientation="portrait" android:theme="@style/OssLicencesTheme" />
		<activity android:launchMode="singleTop" android:name="com.rob.plantix.debug.QaDebugActivity" android:screenOrientation="portrait" android:theme="@style/Base.Theme.Debug" />
		<activity android:name="com.rob.plantix.debug.activities.DebugPesticideCalculatorActivity" android:theme="@style/Base.Theme.Debug" />
		<activity android:name="com.rob.plantix.debug.activities.DebugIndicatorsActivity" android:theme="@style/Base.Theme.Debug" />
		<activity android:name="com.rob.plantix.debug.activities.DebugTokenizationActivity" android:theme="@style/Base.Theme.Debug" />
		<activity android:name="com.rob.plantix.debug.activities.DebugCropColorActivity" android:theme="@style/Base.Theme.Debug" />
		<activity android:name="com.rob.plantix.debug.activities.DebugExifActivity" android:theme="@style/Base.Theme.Debug" />
		<activity android:name="com.rob.plantix.debug.activities.DebugPostRequestActivity" android:theme="@style/Base.Theme.Debug" />
		<activity android:name="com.rob.plantix.debug.activities.DebugMaterial3ThemeActivity" android:theme="@style/Base.Theme.M3" android:windowSoftInputMode="adjustResize" />
		<activity android:name="com.rob.plantix.debug.activities.DebugDukaanPromotedVideosMapperActivity" android:theme="@style/Base.Theme.M3" />
		<activity android:name="com.rob.plantix.debug.activities.DebugDukaanPromotedVideosPreviewActivity" android:theme="@style/Base.Theme.M3" />
		<activity android:name="com.rob.plantix.debug.activities.DebugAnimatedVectorsActivity" android:theme="@style/Base.Theme.Debug" />
		<activity android:name="com.rob.plantix.debug.activities.DebugOpenPostActivity" android:theme="@style/Base.Theme.Debug" />
		<activity android:name="com.rob.plantix.debug.activities.DebugExtractDatabaseFileActivity" android:theme="@style/Base.Theme.Debug" />
		<activity android:name="com.rob.plantix.debug.activities.DebugStaticTooltipBoxActivity" android:theme="@style/Base.Theme.Debug" />
		<activity android:name="com.rob.plantix.debug.activities.DebugRecyclerViewTooltipBoxActivity" android:theme="@style/Base.Theme.Debug" />
		<activity android:name="com.rob.plantix.debug.activities.DebugPathogenPicturesActivity" android:theme="@style/Base.Theme.Debug" />
		<activity android:name="com.rob.plantix.debug.activities.DebugRemoteConfigValuesActivity" android:screenOrientation="portrait" android:theme="@style/Base.Theme.Debug" />
		<activity android:name="com.rob.plantix.debug.activities.DebugLoadBitmapWithCoilActivity" android:theme="@style/Base.Theme.Debug" />
		<activity android:name="com.rob.plantix.debug.activities.DebugPathogenListActivity" android:screenOrientation="portrait" android:theme="@style/Base.Theme.Debug" />
		<activity android:name="com.rob.plantix.debug.activities.DebugProductSearchActivity" android:screenOrientation="portrait" android:theme="@style/Base.Theme.Debug" />
		<activity android:name="com.rob.plantix.debug.activities.DebugTextToSpeechActivity" android:screenOrientation="portrait" android:theme="@style/Base.Theme.Debug" />
		<activity android:name="com.rob.plantix.debug.activities.DebugTextToSpeechMediaPlayerActivity" android:screenOrientation="portrait" android:theme="@style/Base.Theme.Debug" />
		<activity android:name="com.rob.plantix.debug.activities.DebugSpeechToTextActivity" android:screenOrientation="portrait" android:theme="@style/Base.Theme.Debug" />
		<activity android:name="com.rob.plantix.debug.activities.DebugSimpleTextToSpeechMediaActivity" android:screenOrientation="portrait" android:theme="@style/Base.Theme.Debug" />
		<activity android:name="com.rob.plantix.debug.activities.DebugFertilizerProductsActivity" android:theme="@style/Base.Theme.Debug" />
		<activity android:name="com.rob.plantix.debug.activities.DebugTextToSpeechSetupActivity" android:theme="@style/Base.Theme.Debug" />
		<activity android:name="com.rob.plantix.debug.activities.DebugButtonColorsActivity" android:screenOrientation="portrait" android:theme="@style/Base.Theme.Debug" />
		<activity android:name="com.rob.plantix.debug.activities.DebugYoutubeViewActivity" android:screenOrientation="portrait" android:theme="@style/Base.Theme.Debug" />
		<activity android:name="com.rob.plantix.debug.activities.DebugSurveyUiActivity" android:screenOrientation="portrait" android:theme="@style/Base.Theme" />
		<activity android:name="com.rob.plantix.debug.activities.DebugYoutubeAspectRatioActivity" android:screenOrientation="portrait" android:theme="@style/Base.Theme.M3" />
		<activity android:name="com.rob.plantix.debug.activities.DebugFieldsMapActivity" android:screenOrientation="portrait" android:theme="@style/Base.Theme.M3" />
		<activity android:name="com.rob.plantix.debug.activities.DebugFieldsPlotterMapActivity" android:screenOrientation="portrait" android:theme="@style/Base.Theme.M3" />
		<activity android:name="com.rob.plantix.debug.activities.DebugMyStoreCardActivity" android:screenOrientation="portrait" android:theme="@style/Base.Theme.M3" />
		<activity android:name="com.rob.plantix.debug.activities.DebugExoplayerActivity" android:screenOrientation="portrait" android:theme="@style/Base.Theme.M3" />
		<activity android:name="com.rob.plantix.debug.activities.DebugExoplayerListActivity" android:screenOrientation="portrait" android:theme="@style/Base.Theme.M3" />
		<activity android:name="com.rob.plantix.debug.activities.DebugExoplayerFragmentsActivity" android:screenOrientation="portrait" android:theme="@style/Base.Theme.M3" />
		<receiver android:exported="true" android:name="com.rob.plantix.PackageUpdateReceiver">
			<intent-filter>
				<action android:name="android.intent.action.MY_PACKAGE_REPLACED" />
			</intent-filter>
		</receiver>
		<provider android:authorities="com.peat.GartenBank.provider" android:exported="false" android:grantUriPermissions="true" android:name="androidx.core.content.FileProvider">
			<meta-data android:name="android.support.FILE_PROVIDER_PATHS" android:resource="@xml/file_provider_file_paths" />
		</provider>
		<provider android:authorities="com.peat.GartenBank.androidx-startup" android:exported="false" android:name="androidx.startup.InitializationProvider">
			<meta-data android:name="com.rob.plantix.app_start.TimberInitializer" android:value="androidx.startup" />
			<meta-data android:name="androidx.emoji2.text.EmojiCompatInitializer" android:value="androidx.startup" />
			<meta-data android:name="androidx.lifecycle.ProcessLifecycleInitializer" android:value="androidx.startup" />
			<meta-data android:name="androidx.profileinstaller.ProfileInstallerInitializer" android:value="androidx.startup" />
		</provider>
		<activity android:name="com.rob.plantix.crop_advisory.CropAdvisoryEventDetailsActivity" android:screenOrientation="portrait" />
		<activity android:name="com.rob.plantix.crop_advisory.NotificationEventDetailsActivity" android:screenOrientation="portrait" />
		<activity android:name="com.rob.plantix.crop_advisory.CropAdvisoryActivity" android:screenOrientation="portrait" android:theme="@style/Base.Theme.M3" />
		<activity android:name="com.rob.plantix.crop_advisory.CategoryWeeksActivity" android:screenOrientation="portrait" />
		<receiver android:name="com.rob.plantix.crop_advisory.notifications.CropAdvisoryEventNotificationReceiver" />
		<activity android:name="com.rob.plantix.chat_bot.ChatBotActivity" android:screenOrientation="portrait" android:theme="@style/Base.Theme.M2toM3" />
		<activity android:name="com.rob.plantix.community.ComposePostActivity" android:screenOrientation="portrait" android:theme="@style/Base.Theme.M3" android:windowSoftInputMode="adjustResize" />
		<activity-alias android:enabled="false" android:exported="true" android:icon="@mipmap/ic_launcher_round" android:label="@string/action_ask_community" android:name="com.rob.plantix.createPostFromGallery" android:targetActivity="com.rob.plantix.community.ComposePostActivity">
			<intent-filter>
				<action android:name="android.intent.action.SEND" />
				<category android:name="android.intent.category.DEFAULT" />
				<data android:mimeType="image/*" />
			</intent-filter>
			<intent-filter>
				<action android:name="android.intent.action.SEND_MULTIPLE" />
				<category android:name="android.intent.category.DEFAULT" />
				<data android:mimeType="image/*" />
			</intent-filter>
		</activity-alias>
		<activity android:name="com.rob.plantix.community.PostDetailsActivity" android:screenOrientation="portrait" android:theme="@style/Base.Theme.M3" android:windowSoftInputMode="adjustResize" />
		<activity android:name="com.rob.plantix.community.CommunityFilterActivity" android:screenOrientation="portrait" android:theme="@style/Base.Theme.M3" />
		<activity android:name="com.rob.plantix.community.CommunityFilterCropSelectionActivity" android:screenOrientation="portrait" android:theme="@style/Base.Theme.M3" />
		<activity android:name="com.rob.plantix.community.CommunityFilterLanguageSelectionActivity" android:screenOrientation="portrait" android:theme="@style/Base.Theme.M3" />
		<receiver android:name="com.rob.plantix.community.notifications.PopularPostNotificationReceiver" />
		<receiver android:name="com.rob.plantix.community.notifications.CommunityNotificationReceiver" />
		<activity android:configChanges="layoutDirection|locale" android:launchMode="singleTop" android:name="com.rob.plantix.community_account.EditProfileActivity" android:screenOrientation="portrait" />
		<activity android:name="com.rob.plantix.diagnosis.DiagnosisActivity" android:screenOrientation="portrait" android:theme="@style/Base.Theme.M3" />
		<activity android:name="com.rob.plantix.diagnosis_gallery.DiagnosisGalleryActivity" android:screenOrientation="portrait" />
		<activity android:name="com.rob.plantix.fertilizer_calculator.FertilizerCalculatorActivity" android:screenOrientation="portrait" android:theme="@style/Base.Theme.M3" />
		<activity android:name="com.rob.plantix.library.LibraryActivity" android:screenOrientation="portrait" android:theme="@style/Base.Theme.M3" />
		<activity android:name="com.rob.plantix.pathogen.PathogenDetailsActivity" android:screenOrientation="portrait" android:theme="@style/Base.Theme.M3" />
		<receiver android:name="com.rob.plantix.pathogen.notifications.PathogenAlertNotificationReceiver" />
		<activity android:name="com.rob.plantix.pathogen_trends.PathogenTrendsActivity" android:screenOrientation="portrait" android:theme="@style/Base.Theme.M3" />
		<activity android:name="com.rob.plantix.partner_dukaan.DukaanActivity" android:screenOrientation="portrait" android:theme="@style/Base.Theme.M3" android:windowSoftInputMode="adjustResize" />
		<activity android:name="com.rob.plantix.partner_dukaan.DukaanFeedbackActivity" android:screenOrientation="portrait" android:theme="@style/Base.Theme.M3" />
		<activity android:name="com.rob.plantix.profit_calculator.ProfitCalculatorActivity" android:screenOrientation="portrait" android:theme="@style/Base.Theme.M3" />
		<activity android:name="com.rob.plantix.plant_protection_product.PlantProtectionProductActivity" android:screenOrientation="portrait" android:theme="@style/Base.Theme.M3" />
		<activity android:name="com.rob.plantix.field_monitoring.FieldScoutingActivity" android:screenOrientation="portrait" android:theme="@style/Base.Theme.M3" />
		<activity android:name="com.rob.plantix.field_monitoring.PestScoutingYellowStemBorerActivity" android:screenOrientation="portrait" android:theme="@style/Base.Theme.M3" />
		<activity android:name="com.rob.plantix.field_monitoring.PestScoutingBollwormActivity" android:screenOrientation="portrait" android:theme="@style/Base.Theme.M3" />
		<activity android:name="com.rob.plantix.weather.WeatherActivity" android:screenOrientation="portrait" android:theme="@style/Base.Theme.M3" />
		<activity android:name="com.rob.plantix.notifications.NotificationActivity" android:screenOrientation="portrait" />
		<activity android:name="com.rob.plantix.fields.MarkFieldActivity" android:screenOrientation="portrait" android:theme="@style/Base.Theme.M3" />
		<activity android:name="com.rob.plantix.fields.FieldDetailsActivity" android:screenOrientation="portrait" android:theme="@style/Base.Theme.M3" />
		<activity android:name="com.rob.plantix.fields.EditFieldDetailsActivity" android:screenOrientation="portrait" android:theme="@style/Base.Theme.M3" />
		<activity android:name="com.rob.plantix.diagnosis_camera.CameraActivity" android:screenOrientation="portrait" android:theme="@style/Base.Theme.Camera" />
		<activity-alias android:enabled="false" android:exported="true" android:icon="@mipmap/ic_launcher_round" android:label="@string/action_health_check" android:name="com.rob.plantix.diagnoseImageFromGallery" android:targetActivity="com.rob.plantix.diagnosis_camera.CameraActivity">
			<intent-filter android:order="1" android:priority="100">
				<action android:name="android.intent.action.SEND" />
				<category android:name="android.intent.category.DEFAULT" />
				<data android:mimeType="image/*" />
			</intent-filter>
		</activity-alias>
		<activity android:name="com.rob.plantix.crop_information.CropInformationActivity" android:screenOrientation="portrait" />
		<activity android:name="com.rob.plantix.focus_crops.FocusCropSelectionActivity" android:screenOrientation="portrait" />
		<receiver android:name="com.rob.plantix.topics.impl.receiver.BoardingNotificationReceiver" />
		<receiver android:name="com.rob.plantix.topics.impl.receiver.CropNotificationReceiver" />
		<receiver android:name="com.rob.plantix.topics.impl.receiver.WeatherDailyNotificationReceiver" />
		<activity android:name="com.rob.plantix.feedback.FeedbackActivity" android:screenOrientation="portrait" android:theme="@style/Base.Theme.M3" android:windowSoftInputMode="adjustResize" />
		<activity android:name="com.rob.plantix.sign_in.SignInActivity" android:screenOrientation="portrait" />
		<activity android:name="com.rob.plantix.sign_in.legacy.SignInActivity" android:screenOrientation="portrait" />
		<activity android:name="com.rob.plantix.partner.PartnerPromotionActivity" android:screenOrientation="portrait" android:theme="@style/Base.Theme.StatusBarNoLightMode" />
		<activity android:name="com.rob.plantix.social.SocialActivity" android:screenOrientation="portrait" />
		<activity android:name="com.rob.plantix.legal.LegalActivity" android:screenOrientation="portrait" />
		<activity android:configChanges="layoutDirection|locale" android:name="com.rob.plantix.boarding.BoardingLanguageActivity" android:screenOrientation="portrait" />
		<activity android:name="com.rob.plantix.boarding.BoardingSlidesActivity" android:screenOrientation="portrait" />
		<activity android:name="com.rob.plantix.boarding.BoardingUserSegmentationActivity" android:screenOrientation="portrait" />
		<activity android:name="com.rob.plantix.boarding.BoardingPermissionsActivity" android:screenOrientation="portrait" />
		<activity android:name="com.rob.plantix.settings.SettingsActivity" android:screenOrientation="portrait" />
		<activity android:configChanges="layoutDirection|locale" android:name="com.rob.plantix.settings.LanguageSettingsActivity" android:screenOrientation="portrait" />
		<activity android:name="com.rob.plantix.settings.CountrySelectionActivity" android:screenOrientation="portrait" />
		<service android:foregroundServiceType="location" android:name="com.rob.plantix.location.MockLocationService" />
		<service android:name="com.uxcam.service.HttpPostService" />
		<provider android:authorities="com.peat.GartenBank.uxcamprovider" android:exported="false" android:name="com.uxcam.UXCamContentProvider" />
		<service android:directBootAware="true" android:exported="false" android:name="com.google.firebase.components.ComponentDiscoveryService">
			<meta-data android:name="com.google.firebase.components:com.google.firebase.perf.FirebasePerfKtxRegistrar" android:value="com.google.firebase.components.ComponentRegistrar" />
			<meta-data android:name="com.google.firebase.components:com.google.firebase.perf.FirebasePerfRegistrar" android:value="com.google.firebase.components.ComponentRegistrar" />
			<meta-data android:name="com.google.firebase.components:com.google.firebase.auth.FirebaseAuthRegistrar" android:value="com.google.firebase.components.ComponentRegistrar" />
			<meta-data android:name="com.google.firebase.components:com.google.firebase.functions.FirebaseFunctionsKtxRegistrar" android:value="com.google.firebase.components.ComponentRegistrar" />
			<meta-data android:name="com.google.firebase.components:com.google.firebase.functions.FunctionsRegistrar" android:value="com.google.firebase.components.ComponentRegistrar" />
			<meta-data android:name="com.google.firebase.components:com.google.firebase.firestore.FirebaseFirestoreKtxRegistrar" android:value="com.google.firebase.components.ComponentRegistrar" />
			<meta-data android:name="com.google.firebase.components:com.google.firebase.firestore.FirestoreRegistrar" android:value="com.google.firebase.components.ComponentRegistrar" />
			<meta-data android:name="com.google.firebase.components:com.google.firebase.messaging.FirebaseMessagingKtxRegistrar" android:value="com.google.firebase.components.ComponentRegistrar" />
			<meta-data android:name="com.google.firebase.components:com.google.firebase.messaging.FirebaseMessagingRegistrar" android:value="com.google.firebase.components.ComponentRegistrar" />
			<meta-data android:name="com.google.firebase.components:com.google.firebase.dynamiclinks.FirebaseDynamicLinksKtxRegistrar" android:value="com.google.firebase.components.ComponentRegistrar" />
			<meta-data android:name="com.google.firebase.components:com.google.firebase.dynamiclinks.internal.FirebaseDynamicLinkRegistrar" android:value="com.google.firebase.components.ComponentRegistrar" />
			<meta-data android:name="com.google.firebase.components:com.google.firebase.database.FirebaseDatabaseKtxRegistrar" android:value="com.google.firebase.components.ComponentRegistrar" />
			<meta-data android:name="com.google.firebase.components:com.google.firebase.database.DatabaseRegistrar" android:value="com.google.firebase.components.ComponentRegistrar" />
			<meta-data android:name="com.google.firebase.components:com.google.firebase.storage.FirebaseStorageKtxRegistrar" android:value="com.google.firebase.components.ComponentRegistrar" />
			<meta-data android:name="com.google.firebase.components:com.google.firebase.storage.StorageRegistrar" android:value="com.google.firebase.components.ComponentRegistrar" />
			<meta-data android:name="com.google.firebase.components:com.google.firebase.appcheck.FirebaseAppCheckKtxRegistrar" android:value="com.google.firebase.components.ComponentRegistrar" />
			<meta-data android:name="com.google.firebase.components:com.google.firebase.appcheck.FirebaseAppCheckRegistrar" android:value="com.google.firebase.components.ComponentRegistrar" />
			<meta-data android:name="com.google.firebase.components:com.google.firebase.iid.Registrar" android:value="com.google.firebase.components.ComponentRegistrar" />
			<meta-data android:name="com.google.firebase.components:com.google.firebase.crashlytics.FirebaseCrashlyticsKtxRegistrar" android:value="com.google.firebase.components.ComponentRegistrar" />
			<meta-data android:name="com.google.firebase.components:com.google.firebase.crashlytics.CrashlyticsRegistrar" android:value="com.google.firebase.components.ComponentRegistrar" />
			<meta-data android:name="com.google.firebase.components:com.google.firebase.sessions.FirebaseSessionsRegistrar" android:value="com.google.firebase.components.ComponentRegistrar" />
			<meta-data android:name="com.google.firebase.components:com.google.firebase.remoteconfig.FirebaseRemoteConfigKtxRegistrar" android:value="com.google.firebase.components.ComponentRegistrar" />
			<meta-data android:name="com.google.firebase.components:com.google.firebase.remoteconfig.RemoteConfigRegistrar" android:value="com.google.firebase.components.ComponentRegistrar" />
			<meta-data android:name="com.google.firebase.components:com.google.firebase.analytics.connector.internal.AnalyticsConnectorRegistrar" android:value="com.google.firebase.components.ComponentRegistrar" />
			<meta-data android:name="com.google.firebase.components:com.google.firebase.installations.FirebaseInstallationsKtxRegistrar" android:value="com.google.firebase.components.ComponentRegistrar" />
			<meta-data android:name="com.google.firebase.components:com.google.firebase.installations.FirebaseInstallationsRegistrar" android:value="com.google.firebase.components.ComponentRegistrar" />
			<meta-data android:name="com.google.firebase.components:com.google.firebase.ktx.FirebaseCommonLegacyRegistrar" android:value="com.google.firebase.components.ComponentRegistrar" />
			<meta-data android:name="com.google.firebase.components:com.google.firebase.FirebaseCommonKtxRegistrar" android:value="com.google.firebase.components.ComponentRegistrar" />
			<meta-data android:name="com.google.firebase.components:com.google.firebase.abt.component.AbtRegistrar" android:value="com.google.firebase.components.ComponentRegistrar" />
			<meta-data android:name="com.google.firebase.components:com.google.firebase.datatransport.TransportRegistrar" android:value="com.google.firebase.components.ComponentRegistrar" />
		</service>
		<activity android:configChanges="keyboard|keyboardHidden|orientation|screenLayout|screenSize" android:name="com.facebook.FacebookActivity" android:theme="@style/com_facebook_activity_theme" />
		<activity android:name="com.facebook.CustomTabMainActivity" />
		<activity android:exported="true" android:name="com.facebook.CustomTabActivity">
			<intent-filter>
				<action android:name="android.intent.action.VIEW" />
				<category android:name="android.intent.category.DEFAULT" />
				<category android:name="android.intent.category.BROWSABLE" />
				<data android:host="cct.com.peat.GartenBank" android:scheme="fbconnect" />
			</intent-filter>
		</activity>
		<service android:enabled="false" android:exported="false" android:name="androidx.camera.core.impl.MetadataHolderService">
			<meta-data android:name="androidx.camera.core.impl.MetadataHolderService.DEFAULT_CONFIG_PROVIDER" android:value="androidx.camera.camera2.Camera2Config$DefaultProvider" />
		</service>
		<activity android:excludeFromRecents="true" android:exported="true" android:launchMode="singleTask" android:name="com.google.firebase.auth.internal.GenericIdpActivity" android:theme="@android:style/Theme.Translucent.NoTitleBar">
			<intent-filter>
				<action android:name="android.intent.action.VIEW" />
				<category android:name="android.intent.category.DEFAULT" />
				<category android:name="android.intent.category.BROWSABLE" />
				<data android:host="firebase.auth" android:path="/" android:scheme="genericidp" />
			</intent-filter>
		</activity>
		<activity android:excludeFromRecents="true" android:exported="true" android:launchMode="singleTask" android:name="com.google.firebase.auth.internal.RecaptchaActivity" android:theme="@android:style/Theme.Translucent.NoTitleBar">
			<intent-filter>
				<action android:name="android.intent.action.VIEW" />
				<category android:name="android.intent.category.DEFAULT" />
				<category android:name="android.intent.category.BROWSABLE" />
				<data android:host="firebase.auth" android:path="/" android:scheme="recaptcha" />
			</intent-filter>
		</activity>
		<service android:enabled="true" android:exported="false" android:name="androidx.credentials.playservices.CredentialProviderMetadataHolder">
			<meta-data android:name="androidx.credentials.CREDENTIAL_PROVIDER_KEY" android:value="androidx.credentials.playservices.CredentialProviderPlayServicesImpl" />
		</service>
		<activity android:configChanges="keyboardHidden|orientation|screenLayout|screenSize" android:enabled="true" android:exported="false" android:fitsSystemWindows="true" android:name="androidx.credentials.playservices.HiddenActivity" android:theme="@style/Theme.Hidden" />
		<activity android:excludeFromRecents="true" android:exported="false" android:name="com.google.android.gms.auth.api.signin.internal.SignInHubActivity" android:theme="@android:style/Theme.Translucent.NoTitleBar" />
		<service android:exported="true" android:name="com.google.android.gms.auth.api.signin.RevocationBoundService" android:permission="com.google.android.gms.auth.api.signin.permission.REVOCATION_NOTIFICATION" android:visibleToInstantApps="true" />
		<uses-library android:name="org.apache.http.legacy" android:required="false" />
		<service android:directBootAware="false" android:enabled="@bool/enable_system_alarm_service_default" android:exported="false" android:name="androidx.work.impl.background.systemalarm.SystemAlarmService" />
		<service android:directBootAware="false" android:enabled="@bool/enable_system_job_service_default" android:exported="true" android:name="androidx.work.impl.background.systemjob.SystemJobService" android:permission="android.permission.BIND_JOB_SERVICE" />
		<service android:directBootAware="false" android:enabled="@bool/enable_system_foreground_service_default" android:exported="false" android:name="androidx.work.impl.foreground.SystemForegroundService" />
		<receiver android:directBootAware="false" android:enabled="true" android:exported="false" android:name="androidx.work.impl.utils.ForceStopRunnable$BroadcastReceiver" />
		<receiver android:directBootAware="false" android:enabled="false" android:exported="false" android:name="androidx.work.impl.background.systemalarm.ConstraintProxy$BatteryChargingProxy">
			<intent-filter>
				<action android:name="android.intent.action.ACTION_POWER_CONNECTED" />
				<action android:name="android.intent.action.ACTION_POWER_DISCONNECTED" />
			</intent-filter>
		</receiver>
		<receiver android:directBootAware="false" android:enabled="false" android:exported="false" android:name="androidx.work.impl.background.systemalarm.ConstraintProxy$BatteryNotLowProxy">
			<intent-filter>
				<action android:name="android.intent.action.BATTERY_OKAY" />
				<action android:name="android.intent.action.BATTERY_LOW" />
			</intent-filter>
		</receiver>
		<receiver android:directBootAware="false" android:enabled="false" android:exported="false" android:name="androidx.work.impl.background.systemalarm.ConstraintProxy$StorageNotLowProxy">
			<intent-filter>
				<action android:name="android.intent.action.DEVICE_STORAGE_LOW" />
				<action android:name="android.intent.action.DEVICE_STORAGE_OK" />
			</intent-filter>
		</receiver>
		<receiver android:directBootAware="false" android:enabled="false" android:exported="false" android:name="androidx.work.impl.background.systemalarm.ConstraintProxy$NetworkStateProxy">
			<intent-filter>
				<action android:name="android.net.conn.CONNECTIVITY_CHANGE" />
			</intent-filter>
		</receiver>
		<receiver android:directBootAware="false" android:enabled="false" android:exported="false" android:name="androidx.work.impl.background.systemalarm.RescheduleReceiver">
			<intent-filter>
				<action android:name="android.intent.action.BOOT_COMPLETED" />
				<action android:name="android.intent.action.TIME_SET" />
				<action android:name="android.intent.action.TIMEZONE_CHANGED" />
			</intent-filter>
		</receiver>
		<receiver android:directBootAware="false" android:enabled="@bool/enable_system_alarm_service_default" android:exported="false" android:name="androidx.work.impl.background.systemalarm.ConstraintProxyUpdateReceiver">
			<intent-filter>
				<action android:name="androidx.work.impl.background.systemalarm.UpdateProxies" />
			</intent-filter>
		</receiver>
		<receiver android:directBootAware="false" android:enabled="true" android:exported="true" android:name="androidx.work.impl.diagnostics.DiagnosticsReceiver" android:permission="android.permission.DUMP">
			<intent-filter>
				<action android:name="androidx.work.diagnostics.REQUEST_DIAGNOSTICS" />
			</intent-filter>
		</receiver>
		<service android:directBootAware="false" android:exported="@bool/enable_gcm_scheduler_default" android:name="androidx.work.impl.background.gcm.WorkManagerGcmService" android:permission="com.google.android.gms.permission.BIND_NETWORK_TASK_SERVICE">
			<intent-filter>
				<action android:name="com.google.android.gms.gcm.ACTION_TASK_READY" />
			</intent-filter>
		</service>
		<service android:enabled="true" android:exported="false" android:name="com.google.android.gms.tagmanager.TagManagerService" />
		<activity android:exported="true" android:name="com.google.android.gms.tagmanager.TagManagerPreviewActivity" android:noHistory="true">
			<intent-filter>
				<data android:scheme="tagmanager.c.com.peat.GartenBank" />
				<action android:name="android.intent.action.VIEW" />
				<category android:name="android.intent.category.DEFAULT" />
				<category android:name="android.intent.category.BROWSABLE" />
			</intent-filter>
		</activity>
		<receiver android:exported="true" android:name="com.google.firebase.iid.FirebaseInstanceIdReceiver" android:permission="com.google.android.c2dm.permission.SEND">
			<intent-filter>
				<action android:name="com.google.android.c2dm.intent.RECEIVE" />
			</intent-filter>
			<meta-data android:name="com.google.android.gms.cloudmessaging.FINISHED_AFTER_HANDLED" android:value="true" />
		</receiver>
		<service android:directBootAware="true" android:exported="false" android:name="com.google.firebase.messaging.FirebaseMessagingService">
			<intent-filter android:priority="-500">
				<action android:name="com.google.firebase.MESSAGING_EVENT" />
			</intent-filter>
		</service>
		<receiver android:enabled="true" android:exported="false" android:name="com.google.android.gms.measurement.AppMeasurementReceiver" />
		<service android:enabled="true" android:exported="false" android:name="com.google.android.gms.measurement.AppMeasurementService" />
		<service android:enabled="true" android:exported="false" android:name="com.google.android.gms.measurement.AppMeasurementJobService" android:permission="android.permission.BIND_JOB_SERVICE" />
		<activity android:exported="false" android:name="com.google.android.gms.common.api.GoogleApiActivity" android:theme="@android:style/Theme.Translucent.NoTitleBar" />
		<activity android:exported="true" android:name="androidx.compose.ui.tooling.PreviewActivity" />
		<provider android:authorities="com.peat.GartenBank.FacebookInitProvider" android:exported="false" android:name="com.facebook.internal.FacebookInitProvider" />
		<receiver android:exported="false" android:name="com.facebook.CurrentAccessTokenExpirationBroadcastReceiver">
			<intent-filter>
				<action android:name="com.facebook.sdk.ACTION_CURRENT_ACCESS_TOKEN_CHANGED" />
			</intent-filter>
		</receiver>
		<receiver android:exported="false" android:name="com.facebook.AuthenticationTokenManager$CurrentAuthenticationTokenChangedBroadcastReceiver">
			<intent-filter>
				<action android:name="com.facebook.sdk.ACTION_CURRENT_AUTHENTICATION_TOKEN_CHANGED" />
			</intent-filter>
		</receiver>
		<property android:name="android.adservices.AD_SERVICES_CONFIG" android:resource="@xml/ad_services_config" />
		<uses-library android:name="android.ext.adservices" android:required="false" />
		<uses-library android:name="androidx.window.extensions" android:required="false" />
		<uses-library android:name="androidx.window.sidecar" android:required="false" />
		<service android:directBootAware="true" android:exported="false" android:name="androidx.room.MultiInstanceInvalidationService" />
		<service android:enabled="true" android:exported="false" android:name="com.google.firebase.sessions.SessionLifecycleService" />
		<provider android:authorities="com.peat.GartenBank.firebaseinitprovider" android:directBootAware="true" android:exported="false" android:initOrder="100" android:name="com.google.firebase.provider.FirebaseInitProvider" />
		<receiver android:directBootAware="false" android:enabled="true" android:exported="true" android:name="androidx.profileinstaller.ProfileInstallReceiver" android:permission="android.permission.DUMP">
			<intent-filter>
				<action android:name="androidx.profileinstaller.action.INSTALL_PROFILE" />
			</intent-filter>
			<intent-filter>
				<action android:name="androidx.profileinstaller.action.SKIP_FILE" />
			</intent-filter>
			<intent-filter>
				<action android:name="androidx.profileinstaller.action.SAVE_PROFILE" />
			</intent-filter>
			<intent-filter>
				<action android:name="androidx.profileinstaller.action.BENCHMARK_OPERATION" />
			</intent-filter>
		</receiver>
		<service android:exported="false" android:name="com.google.android.datatransport.runtime.backends.TransportBackendDiscovery">
			<meta-data android:name="backend:com.google.android.datatransport.cct.CctBackendFactory" android:value="cct" />
		</service>
		<service android:exported="false" android:name="com.google.android.datatransport.runtime.scheduling.jobscheduling.JobInfoSchedulerService" android:permission="android.permission.BIND_JOB_SERVICE" />
		<receiver android:exported="false" android:name="com.google.android.datatransport.runtime.scheduling.jobscheduling.AlarmManagerSchedulerBroadcastReceiver" />
		<activity android:exported="false" android:name="com.google.android.play.core.common.PlayCoreDialogWrapperActivity" android:stateNotNeeded="true" android:theme="@style/Theme.PlayCore.Transparent" />
	</application>
</manifest>
