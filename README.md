# ChainCatcher RSS

RSS document that includes in-depth articles and real-time news.

## RSS Document Introduction

ChainCatcher RSS is an RSS feed file that includes in-depth articles and real-time news. ChainCatcher will automatically grab the latest published articles on the website and put them into the RSS feed.

## RSS Format

The RSS interface format is an XML document containing the following elements [attached_file:2]:

- **channel**: RSS information document.
  - **title**: channel title ("链捕手")
  - **link**: channel URL (https://www.chaincatcher.com)
  - **description**: channel description
  - **language**: zh-cn
  - **item**: Contains information about an article.
    - **title**: Article title (CDATA)
    - **link**: Article URL
    - **description**: Article summary (CDATA)
    - **content:encoded**: Full HTML content
    - **category**: 快讯 or 文章
    - **pubDate**: Publication date
    - **guid**: Article URL

## Use Example

**RSS URL**: https://www.chaincatcher.com/rss/clist [attached_file:2]

Example response:

```xml
<?xml version="1.0" encoding="UTF-8"?>
<rss xmlns:content="http://purl.org/rss/1.0/modules/content/" xmlns:dc="http://purl.org/dc/elements/1.1/" version="2.0">
  <channel>
    <title>链捕手</title>
    <link>https://www.chaincatcher.com/</link>
    <description>链捕手ChainCatcher...</description>
    <item>
      <title><![CDATA[加密市场低迷冲击ARK ETF 2025年Q4表现...]]></title>
      <link>https://www.chaincatcher.com/article/2237625</link>
      <description><![CDATA[ChainCatcher 消息，据市场消息...]]></description>
      <category>快讯</category>
      <pubDate>Thu, 15 Jan 2026 09:19:58 +0100</pubDate>
      <guid>https://www.chaincatcher.com/article/2237625</guid>
    </item>
  </channel>
</rss>

## Subscription Links

| Channel | RSS URL                                      |
|---------|----------------------------------------------|
| Latest  | https://www.chaincatcher.com/rss/clist [attached_file:2] |

## How to Subscribe

- **Browser**: Paste URL directly (Chrome/Edge/Firefox)
- **Readers**: Feedly, Inoreader, NewsBlur  
- **Mobile**: Feedly App, Reeder (iOS)

