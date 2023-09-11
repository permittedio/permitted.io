---
permalink: /
title: "Unleash the power of real-time Floating Licensing platform"
author_profile: false
layout: splash
classes:
    - landing
    - wide
header:
  overlay_color: "#000"
  overlay_filter: "0.125"
  overlay_image: /assets/images/splash/splashhomepage.jpg
  actions:
    - label: "Create a free account"
      url: "/start"
excerpt: "Empowering your software usage with real-time Floating Licensing" 
intro:
  - excerpt: permitted.io is not just a licensing platform; it’s a paradigm shift in how software licensing should work.
feature_row:
  - image_path: /assets/images/splash/developer.svg
    title: Seamless Scalability
    excerpt: Say goodbye to limitations. Our cloud platform scales seamlessly with your needs. Whether you're a startup dreaming big or a multinational corporation, we've got you covered. Grow with confidence. As your team expands, your licensing solution grows with you.
    ## url: "#test-link"
    ## btn_label: "Read More"
    ## btn_class: "btn--secondar"
  - image_path: /assets/images/splash/deploy.svg
    title: Reliability and Uptime
    excerpt: Downtime is not an option. With permitted.io, you'll enjoy unparalleled reliability and minimal downtime. Our cloud-based platform ensures your applications are always accessible.
    # url: "#test-link"
    # btn_label: "Read More"
    # btn_class: "btn--secondar"
  - image_path: /assets/images/splash/launch.svg
    title: Enhanced Productivity
    excerpt: Boost productivity across your organization. permitted.io is a Real-Time Floating Licensing platform and ensures that your software is readily available to authorized users, eliminating downtime and delays caused by license bottlenecks.
    # url: "#test-link"
    # btn_label: "Read More"
    # btn_class: "btn--secondar" 

feature_row_right1:
  - image_path: /assets/images/cloud.svg
    title: "Real-Time Adaptability"
    excerpt: permitted.io provides licenses on-demand, allocating them to users in real-time. Whether it’s a busy workday or a quiet weekend, licenses automatically adjust to match the number of users requiring access. No more idle licenses during off-peak hours.

feature_row_left1:
  - image_path: /assets/images/flexibility_software.svg
    title: Easy Integration
    excerpt: permitted.io seamlessly integrates with your existing software systems by its API, whether it’s proprietary software or popular third-party applications. Implementation is hassle-free, and our support team is ready to assist every step of the way.

feature_row_right2:
  - image_path: /assets/images/cloud.svg
    title: "Platform Agnostic"
    excerpt: Connect applications regardless of the technology stack they’re built on. From iOS and Android to web and desktop, permitted.io’s node, web, and .NET APIs ensure compatibility without constraints.

feature_row_left2:
  - image_path: /assets/images/flexibility_software.svg
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
    connection.Url = "http://app.permitted.io/api";
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
   Key = "NotNeeded",
   UserId = "1037fbf5-dfce-4082-9f18-e323bddc7719|B|C|D|E", //Example pattern: TenantId|AppId|LicKey|ComponentId|UserId
   Url = "https://app.permitted.io/api"
  },cancellationToken);
```
## Our APIs are cross-platform

{: .text-center-left}

Elevate your application's floating licensing needs with our cross-platform Web API, .NET API and node API simplifying development by providing a single, versatile interface for diverse platforms, ensuring consistent performance and functionality across the digital landscape.



{% include feature_row %}

## Web is the epicenter

{: .text-center-left}

permitted.io platform employs an array of technologies to not only serve desktop apps, but also web and mobile apps. It offers interesting solutions to problems like session tracking in web browsers on multiple instances or tabs. Leverage this contemporary platform to implement simple solutions for your challenges in JavaScript technology stacks.