---
permalink: /
title: "A reimagined Licensing-as-a-Service to empower real-time floating licensing"
author_profile: false
layout: splash
classes:
    - landing
    - wide
header:
  overlay_color: "#000"
  overlay_filter: "0.125"
  overlay_image: /assets/images/splash/home_page_splash.jpg
  actions:
    - label: "Create a free account"
      url: "/start"
excerpt: "permitted.io is not just a licensing platform; it’s a paradigm shift in how software licensing should work!"
intro:
  - excerpt: "Get a strong grip on your software usage with permitted.io real-time floating licensing platform" 
feature_row:
  - image_path: /assets/images/cloud.jpg
    title: Seamless Scalability
    excerpt: Say goodbye to limitations. Our cloud platform scales seamlessly with your needs. Whether you're a startup dreaming big or a multinational corporation, we've got you covered. Grow with confidence. As your team expands, your licensing solution grows with you.
    ## url: "#test-link"
    ## btn_label: "Read More"
    ## btn_class: "btn--secondar"
  - image_path: /assets/images/uptime.svg
    title: Reliability and Uptime
    excerpt: Downtime is not an option. With permitted.io, you'll enjoy unparalleled reliability and minimal downtime. Our cloud-based platform ensures our floating licensing platform is available to your applications at %99.9 of the time.
    # url: "#test-link"
    # btn_label: "Read More"
    # btn_class: "btn--secondar"
  - image_path: /assets/images/productivity.svg
    title: Enhanced Productivity
    excerpt: Boost productivity across your organization. permitted.io is a Real-Time Floating Licensing platform and ensures that your software is readily available to authorized users, eliminating downtime and delays caused by license bottlenecks.
    # url: "#test-link"
    # btn_label: "Read More"
    # btn_class: "btn--secondar" 

feature_row_right1:
  - image_path: /assets/images/real-time.svg
    title: "Real-Time Adaptability"
    excerpt: permitted.io provides licenses on-demand, allocating them to users in real-time. Whether it’s a busy workday or a quiet weekend, licenses automatically adjust to match the number of users requiring access. No more idle licenses during off-peak hours.

feature_row_left1:
  - image_path: /assets/images/code-integration.svg
    title: Easy Integration
    excerpt: permitted.io, as a Licensing-as-a-Service, seamlessly integrates with your existing software systems with its API, whether it’s a proprietary software or popular third-party applications. Implementation is hassle-free, and our support team is ready to assist every step of the way.

feature_row_right2:
  - image_path: /assets/images/agnostic.svg
    title: "Platform Agnostic"
    excerpt: Connect applications regardless of the technology stack they’re built on. From iOS and Android to web and desktop, permitted.io’s node, web, and .NET APIs ensure compatibility without constraints.

feature_row_left2:
  - image_path: /assets/images/dashboard.svg
    title: Centralized Management
    excerpt: A user-friendly dashboard gives you complete control over license allocation, usage data, and user access. Manage licenses, track utilization, and make data-driven decisions with ease.
  
# feature_row_techs:
#   - image_path: assets/images/splash/azure100x100.png
#   - image_path: assets/images/splash/NET_logo.png
#   - image_path: /assets/images/splash/angular100.png
#   - image_path: assets/images/splash/ts-logo-100.png
#   - image_path: assets/images/splash/terraform_logo.png

---

{% include feature_row id="intro" type="center" %}
{% include feature_row id="feature_row_right1" type="right" %}
{% include feature_row id="feature_row_left1" type="left" %}
{% include feature_row id="feature_row_right2" type="right" %}
{% include feature_row id="feature_row_left2" type="left" %}

# A future-proof floating license platform

Say goodbye to rigid, device-bound licenses and hello to the future of software flexibility, efficiency, and cost savings. Embrace the power of real-time floating licensing with permitted.io and take control of your software usage like never before.

Technology evolves rapidly. With permitted.io, you're always at the forefront of innovation. We regularly update our platform to incorporate the latest advancements, keeping you ahead of the competition.

Ready to propel your business to new heights? Choose permitted.io and embark on a journey of growth, efficiency, and success like never before. Join the ranks of industry leaders who trust us to revolutionize their operations

---

# Seamless code integration

Our platform seamlessly integrates with your existing systems, ensuring a smooth transition and minimal disruption to your operations. Our simple to use APIs allow you to license your web and desktop applications with a mimimal amount of coding efforts.

## typescript

```typescript
    const connection = new ConnectionParameters();
    connection.AccessKey = 'myKey';
    connection.UserId = "myUserId";
    connection.LicensingEndpoint = "https://licensing.permitted.io/api";
    const seat = new SeatTracker(hub, logger);
    await seat.start(connection);
```

## C# .NET

```cs
  var cancellationToken = new CancellationToken();
  using var subscription = _session.OnLicenseEvent.Subscribe(session =>
  {
      if(session.LicenseMessage == LicenseMessage.Licensed)
      {
      }
      if(session.LicenseMessage == LicenseMessage.NotLicensed)
      {
      }
      if(session.LicenseMessage == LicenseMessage.Error)
      {
      }
  },
  error =>
  {
      finish = true;
  },
  () =>
  {
  });
  await _session.StartAsync(new()
  {
      AccessKey = "myKey",
      UserId = "myUserId",
      LicensingEndpoint = "https://licensing.permitted.io/api"
  },cancellationToken);
```

## Our APIs are cross-platform

{: .text-left}

Elevate your application's floating licensing needs with our cross-platform Web API, .NET API and node API simplifying development by providing a single, versatile interface for diverse platforms, ensuring consistent performance and functionality across the digital landscape.

{% include feature_row %}

# Web is the epicenter
{: .text-center}

permitted.io's platform employs an array of technologies to not only serve desktop apps, but also web and mobile apps. It offers interesting modern solutions to problems like real-time user session tracking multiple instances of web browsers or a browser's tabs. Leverage our contemporary platform and the `node` SDK to implement simple solutions for your challenges in JavaScript technology stacks.
{: .text-center}

---

# Service plans and subscriptions
{: .text-center}


|Monthly plan |Annual plan|Premium plan|
| ----------- | ----------- |---|
|Unlimitted applications to license|Unlimitted applications to license|Tailored to the requirements|
|Unlimitted license models per application|Unlimitted license models per application|Tailored to the requirements|
|Unlimitted users per license pool|Unlimitted users per license pool|Tailored to the requirements|
|Multiple or single session(s) per user|Multiple or single session(s) per user|Tailored to the requirements|
|License validity period|License validity period|License validity period|
|Unlimitted users to license|Unlimitted users to license|Tailored to the requirements|
|Real-time user session tracking|Real-time user session tracking|Real-time user session tracking [^2]|
|Ability to define trial licenses|Ability to define trial licenses|Tailored to the requirements|
|Exclusive access to our SDKs' GitHub repos|Exclusive access to our SDKs' GitHub repos|Exclusive access to our SDKs' GitHub repos|
|Access to technical documentation|Access to technical documentation|Access to technical documentation|
|99.9% up time|99.9% up time|[Please contact us](/contact)|
|N/A|N/A|A replica of our system on cloud|
|2 support ticket per month|30 support tickets per year|Premium support|
|7-day free trial|7-day free trial|[Please contact us](/contact)|
|**US$500 per month**|**US$5000 per year**|[Please contact us](/contact)|
|<a href="#" class="btn btn--success btn--large">Create a free account</a>|<a href="#" class="btn btn--success btn--large">Create a free account</a>|[Please contact us](/contact)|

You agree with our terms and conditions and privacy policy when creating an account.