Shipping Cost Calculator App
=======

A modular and extensible shipping cost calculator app for Liferay using OSGi. The app consists of the following modules:

* **shipping-api:** Contains only the interfaces of the OSGi services that make up the app.
* **shipping-impl:** Contains the implementation of the core OSGi services of the app.
* **shipping-web:** Contains the user interface of the app.
* **shipping-extension-europe:** An OSGi service to extend the shipping app with options for Europe.
* **shipping-extension-usa:** An OSGi service to extend the shipping app with options for the USA.

## Installation

* Obtain the Liferay Plugins SDK from the 6.2.x branch of the [Liferay Plugins repository](https://github.com/liferay/liferay-plugins).
* Create an app/shipping folder in the root level the Liferay Plugins SDK.
* Obtain and copy all the shipping project modules to that folder.
* Deploy all modules. Read the [Liferay Developer Guide](https://www.liferay.com/es/documentation/liferay-portal/6.2/development/-/ai/leveraging-the-plugins-sdk-liferay-portal-6-2-dev-guide-02-en) for more information about working with Liferay plugins and the SDK.

