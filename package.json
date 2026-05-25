import { defineConfig } from 'vitepress'

export default defineConfig({
  title: "7AI 智算相关文档",
  description: "从网页聊天到本地部署，一页讲清楚",
  ignoreDeadLinks: true, // ⚠️免死金牌：允许空目录存在，不会导致网站崩溃
  themeConfig: {
    nav: [
      { text: '首页', link: '/' },
      { text: '控制台', link: 'https://api.7ai.one' },
      { text: '网页聊天', link: 'https://chat.7ai.one' }
    ],
    sidebar: [
      {
        text: '入门',
        collapsed: false, // 默认展开
        items: [
          { text: '引言', link: '/guide/intro' },
          { text: '快速开始', link: '/guide/quick-start' },
          { text: 'Base URL / API Key / CDK', link: '/guide/base-url' },
          { text: '网页聊天', link: '/guide/web-chat' },
          { text: '模型分组和倍率', link: '/guide/models' },
          { text: '钱包和 CDK', link: '/guide/wallet' },
          { text: 'API Key 管理', link: '/guide/apikey' }
        ]
      },
      {
        text: '本地接入',
        collapsed: false,
        items: [
          { text: '接入前确认', link: '/integration/pre-check' },
          { text: 'ChatBox', link: '/integration/chatbox' },
          { text: 'Cherry Studio', link: '/integration/cherry-studio' },
          { text: 'AionUI', link: '/integration/aionui' },
          { text: 'Lobe Chat', link: '/integration/lobe-chat' },
          { text: 'AI as Workspace', link: '/integration/ai-workspace' },
          { text: 'AMA 问天', link: '/integration/ama' },
          { text: 'OpenCat', link: '/integration/opencat' }
        ]
      },
      {
        text: '开发和排错',
        collapsed: false,
        items: [
          { text: '代码项目接入', link: '/dev/code' },
          { text: '部署失败排查', link: '/dev/troubleshoot' },
          { text: '常见问题', link: '/dev/faq' },
          { text: '参考资料', link: '/dev/references' }
        ]
      }
    ]
  }
})
