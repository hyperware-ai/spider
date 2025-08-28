# spider

Spider is the central orchestrator for the web of LLM-powered applications on Hyperware

![spider](https://raw.githubusercontent.com/hyperware-ai/spider/refs/heads/master/assets/spider-512-y.png)

## Status

[Read the roadmap here](https://gist.github.com/nick1udwig/117f9fc5bfd134f987183dd7c67343b4)

[Read a non-technical discussion of the vision here](https://gist.github.com/nick1udwig/147827a2d7d4f432ed186f6b2085a939)

## Building

Depends on https://github.com/hyperware-ai/anthropic-api-key-manager

First build and put that app on a fakenode; then build spider:

```
# In a terminal, start a fakenode:
kit f

# In another terminal, build and install the API key manager:
kit b --hyperapp && kit s

# Then build Spider:
cd ~/git/spider
kit b --hyperapp
```

## Screenshots

![chat](https://raw.githubusercontent.com/hyperware-ai/spider/refs/heads/master/assets/spider-chat.png)
![mcp-servers](https://raw.githubusercontent.com/hyperware-ai/spider/refs/heads/master/assets/spider-mcp-servers.png)
![api-keys](https://raw.githubusercontent.com/hyperware-ai/spider/refs/heads/master/assets/spider-api-keys.png)
![llm-api-keys](https://raw.githubusercontent.com/hyperware-ai/spider/refs/heads/master/assets/spider-llm-api-keys.png)
