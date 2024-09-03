# Project Influencer Meet

### Personal Opinion

It is a Website integrating professionals/influencers and their audience(From Different Platforms) on a single platform for a variety of services such as paid 1:1 Video Sessions and money costing Priority DMs etc. The owner of the site earns commission through these and increases or decreases commission by the provided number of Services.

## Pages

1. Home Page
2. Sign Up/In (Google Login, Linkdin Login, Custom Login)(Need to Connect Social Account, Availability Timing, whatsapp number)
3. Essentials (For Creators, Pricing, Earnings Calculator)
4. Legal Pages (About Us, Contact Us, Terms Of Service, Privacy, Pricing, Blog)
5. DashBoard For Admin (Need to connect payout, create a service, share a post)
6. Dashboard for account Owner
7. Pages for Video Calling interface (Maybe)

## Pricing

1. 7% Commission - Basic
2. 10% Commission - Premium

## API Used

1. Google Meet
2. Zoom Pro
3. Personal Link

## Services By Creators

1. 1:1 Sessions
2. Priority DMs
3. Webinars
4. Packages
5. Digital Products

## Services for creators

1. Calender
2. Analytics
3. Dashboard to view Services for users
4. Marketing (Email, Whatsapp, Funnels)
5. Payments and Checkout
6. Profile
7. Rewards
8. Whats New
9. Ability to share a post on different Platforms (Linkedin, Twitter, Instagram)

## Services For Users

1. Testimonials
2. Bookings
3. Priority DM

## Budget

Google Meet API (it does not incur charges until we use it past its limits) : Free for 600 read and 100 write requests per minute per user

AWS Server:
t4g.medium (Location: Asia(Hyderabad)),
On Demand(hourly rate) - $0.0224 (INR 1.88),
Cores - 2,
Memory - 4 GiB,
Storage - EBS Only,
Network Performance - Up to 5 Gigabit,

[Amazon EC2 Link](https://aws.amazon.com/ec2/pricing/on-demand/)

Monthly Cost : INR 1372 (excluding data transfer and API cost)

### Google API

[Google APi Usage Charges](https://developers.google.com/meet/api/guides/limits)

[Google Meet Rest API Reference](https://developers.google.com/meet/api/reference/rest/v2)

[Youtube API Guide](https://www.youtube.com/watch?v=S1oGdUvgfSc)

#### Limits

- Read requests
  Per minute per project 6000
  Per minute per user per project 600

- Write requests
  Per minute per project 1000
  Per minute per user per project 100

- Reduced write requests
  (Used for spaces.create requests.)
  Per minute per project 100
  Per minute per user per project 10

### Server

Will be Decided Before Project Development Starts

### Login/SignUp API

#### Google Login API

[Google Sign In API Reference Docs](https://developers.google.com/identity/sign-in/web/sign-in)

#### Linkedin API

[Linkedin API Documentation By Microsoft](https://learn.microsoft.com/en-us/linkedin/?context=linkedin%2Fcontext)

### APIs for other websites (Instagram, Linkedin, Whatsapp) Post

[Content Publishing API For instagram](https://developers.facebook.com/docs/instagram-platform/instagram-api-with-facebook-login/content-publishing/)

[Linkedin OpenID Connect and Share](https://learn.microsoft.com/en-us/linkedin/consumer/integrations/self-serve/sign-in-with-linkedin-v2)

[GFG Tutorial for sharing on Whatsapp](https://www.geeksforgeeks.org/how-to-add-whatsapp-share-button-on-a-website/)

### SEO/Marketing/Tracking APIs

MArketing and tracking will be in- house for now

[SEO Solutions](https://rapidapi.com/collection/seo-api)

### Payment Gateway Integration

we are going to use paypals payflow payment gateway

[payflow integration Guide](https://developer.paypal.com/api/nvp-soap/payflow/integration-guide/)
[payflow integration Guide PDF](https://www.paypalobjects.com/webstatic/en_US/developer/docs/pdf/pp_payflowlink_guide.pdf)

# Project Plan

31 Aug to 6 Sep : Research
9 Sep to 13 Sep : Development
16 Sep to 20 Sep : Alpha Testing
23 Sep to 27 Sep : Beta Testing
30 Sep : Production Release

## Research Tasks

1. Video API Documentation
2. Budgetung
3. Competition Analysis
4. Business Structure analysis
5. Development Process Documentation

### Competition Analysis

Personal Opinion : TopMate in its category the best site, oushining all the competition. But still the competition provides same functionality with a different theme for other sectors such as online coaching and selling courses.

#### [Superpeer](https://superpeer.com)

Superpeer specializes in community engagement and monetization for creators within various sectors such as education and coaching. The company offers tools for hosting livestreams, creating and selling online courses, managing one-on-one video calls, and facilitating digital product sales. Superpeer primarily serves creators looking to monetize their content and engage with their audience through subscriptions and interactive features. It was founded in 2020 and is based in Mountain View, California. In March 2024, Superpeer was acquired by Skillshare.

#### [Canopy](https://underthecanopy.io/)

Canopy focuses on the creator economy. It provides an anonymous but verified community for content creators to share knowledge, grow their careers, and engage in discussions in a safe environment. The company primarily serves the content creation industry. It was founded in 2022 and is based in New York, New York.

#### [Creator Stack](https://creatorstack.com/)

CreatorStack is a platform focused on empowering content creators within the creator economy sector. The company offers tools for creators to engage with their audience, monetize their content through royalties, and access resources to build and grow their creative ventures. CreatorStack primarily serves individuals and businesses in the creator economy, providing them with the means to manage their brand and audience relationships more independently. It was founded in 2019 and is based in Bengaluru, India.

#### [Teachable](https://teachable.com/)

Teachable provides an online platform for freelancers and creators to create and sell online courses and coaching services. It offers a drag-and-drop builder, a customizable sales page builder, and direct integrations for users to optimize student engagement. The company develops a product named Vizia offering video solutions. It was formerly known as Fedora. The company was founded in 2014 and is based in New York, New York. in March 2020, Teachable was acquired by Hotmart.

#### [Crowd Cast](https://crowdcast.io/)

Crowdcast is an online events platform operating in the technology sector. The company provides services that allow businesses and individuals to host a variety of events such as Q&As, workshops, live shows, meet-ups, webinars, online concerts, and online summits. Crowdcast primarily serves businesses, creators, and the general public. It was founded in 2015 and is based in San Francisco, California.

### Business Structure Analysis

1. We are going to structure our business as Commission based with a standard commission and a premium commission.
2. The website will Scale depending on the number of the users on the platform.
3. Since its a Business to Business Platform the commission are guranteed of the Businesses accessing the website bring in the audience themselves. it saves the hassle of growing the SEO ourselves.
4. The Operation Cost of the website is minimal since we will be paying only the website hosting costs and Payment gateway cost (which also has a free tier). Heavy loading is done by the Google Meet Platform.

- Personal Opinion: All n all this website if created correctly should bring in revenue but we need to be ahead of the competition in terms of UI and features.
