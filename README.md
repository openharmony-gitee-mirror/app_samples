# App Samples<a name="EN-US_TOPIC_0000001115464207"></a>

-   [Introduction](#section1470103520301)
-   [Usage](#section17988202503116)
-   [Limitations](#section18841871178)
-   [Repositories Involved](#section741114082513)

## Introduction<a name="section1470103520301"></a>

We provide a series of app samples to help you quickly get familiar with the APIs and app development process of the HarmonyOS and OpenHarmony SDKs. Each app sample is an independent project in DevEco Studio. You can import a project into DevEco Studio to learn how to use APIs in the sample by browsing code, building the project, and installing and running the app.

## Usage<a name="section17988202503116"></a>

1.  Import an independent app sample project into DevEco Studio for compilation, building, running, and debugging.
2.  Some samples contain multiple modules. You can compile and build a single module to generate a HAP file or compile and build the entire project to generate multiple HAP files.
3.  After HAP installation and execution, you can view the execution effect of the sample on the device and then conduct debugging.

## Limitations<a name="section18841871178"></a>

1.  Before installing and running the sample, check the  **deviceType**  field in the  **config.json**  file to obtain the device types supported by the sample. You can modify this field to enable the sample to run on your target device. \(The  **config.json**  file is generally stored in the  **entry/src/main**  directory, which may be different depending on the samples.\)
2.  If you want to run the app sample on HarmonyOS, configure the development environment by referring to  [HUAWEI DevEco Studio User Guide](https://developer.harmonyos.com/en/docs/documentation/doc-guides/tools_overview-0000001053582387). If you want to run the app sample on OpenHarmony, configure the development environment by referring to  [DevEco Studio \(OpenHarmony\) User Guide](https://gitee.com/openharmony/docs/blob/master/en/application-dev/quick-start/Readme-EN.md).
3.  App samples that can run on standard-system or small-system devices (as stipulated in **Readme**) must run on OpenHarmony, whereas those that can run on large-system devices must run on HarmonyOS.
4.  All app samples that must run on HarmonyOS have been migrated to the [harmonyos\_app\_samples](https://gitee.com/harmonyos/harmonyos_app_samples) repository in the [HarmonyOS community](https://gitee.com/harmonyos). These samples will no longer be updated in the current repository and will be removed soon.

## Repositories Involved<a name="section741114082513"></a>

1.  App samples of the **CAMERA\_SAMPLE\_APP** module: [applications\_sample\_camera](https://gitee.com/openharmony/applications_sample_camera/blob/master/README.md)
2.  App samples of the **WIFI\_IOT\_APP** module: [applications\_sample\_wifi\_iot](https://gitee.com/openharmony/applications_sample_wifi_iot/blob/master/README.md)
3.  HarmonyOS app samples: [harmonyos\_app\_samples](https://gitee.com/harmonyos/harmonyos_app_samples)
