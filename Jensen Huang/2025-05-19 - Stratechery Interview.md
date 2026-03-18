# Jensen Huang - Stratechery Interview 2025

**Date:** May 19, 2025  
**Event:** Stratechery Interview (Post-Computex 2025)  
**Location:** Taipei, Taiwan  
**Interviewer:** Ben Thompson  
**Source:** Stratechery  
**Tags:** #jensen-huang #persona #transcript #stratechery #ben-thompson #enterprise

---

## Key Insights

- **NVIDIA full-stack approach maximizes utility** — Hardware, software, systems work together
- **Dynamo improves inference performance** — Optimizes distributed inference across GPUs
- **Enterprise pragmatism** — Companies want ROI, not complexity
- **Sell what customers want** — Full-stack or individual components
- **Gaming remains strategically important** — Still the testbed for future technologies

---

## Notable Quotes

> "We want to sell to both — hyperscalers and enterprises. That's the NVIDIA strategy."

> "Full-stack means everything works together. But disaggregated means the ecosystem can work with us."

> "Dynamo improves inference performance by optimizing token routing across distributed GPUs."

> "Every GPU generation gets faster. That's the magic of accelerated computing."

> "Enterprise customers want pragmatism. They want ROI, not just technology."

> "We don't force full-stack. We offer full-stack and components. Customers choose."

> "The hyperscaler strategy and the enterprise strategy are complementary, not competing."

---

## Interview Transcript

### Opening: A Different Keynote

**Ben Thompson:** I've seen you present GTC and Computex keynotes this year. They felt very different.

**Jensen Huang:** They were designed for different audiences. GTC in March was for American hyperscalers. Computex today was for Taiwan OEMs and enterprise customers worldwide.

Same technology, different framing. The hyperscalers care about scale, efficiency, training infrastructure. The OEMs and enterprises care about deployment, integration, time-to-market.

We want to sell to both. That's the NVIDIA strategy.

### Full-Stack vs Open

**Ben Thompson:** You've been criticized for being too vertically integrated. How do you respond?

**Jensen Huang:** Two things:

First, full-stack means everything works together. When we design hardware, software, networking, systems as a unit, we maximize performance. Customers get better results.

Second — and this is crucial — we're also disaggregated. CUDA runs on any GPU. Our networking works with other systems. Customers can use just the pieces they want.

We don't force full-stack. We offer it as an option. Many customers want it. Some don't. That's fine.

The ecosystem matters. Partners matter. We're building infrastructure that others can build on.

### Dynamo and Inference

**Ben Thompson:** You announced Dynamo. What is it?

**Jensen Huang:** Dynamo is our inference serving framework. It optimizes how tokens flow through distributed GPU clusters.

Here's the thing: inference is hard. It's not just about having fast GPUs. It's about routing, load balancing, efficiency at scale.

Dynamo intelligently routes tokens across GPUs, spreading work to keep all units busy. It minimizes latency while maximizing throughput. It handles the complexity of distributed inference so customers don't have to.

**Ben Thompson:** Is this about competing with inference providers like Together or Fireworks?

**Jensen Huang:** Not directly. They can use Dynamo too. We're enabling the entire ecosystem.

Our goal is to make inference efficient on NVIDIA infrastructure. Whether companies run their own inference or use a service, Dynamo helps.

### Hardware and Software Co-Design

**Ben Thompson:** How does the software-hardware interplay work?

**Jensen Huang:** It's fundamental to our approach.

When we design Blackwell, we're not just thinking about transistors. We're thinking about how software will use those transistors.

For example: FP4 support. We didn't just add FP4 because it sounded good. We worked with customers to understand what precision they actually need for inference. Then we optimized the hardware for it.

The second-generation Transformer Engine in Blackwell — that came from understanding bottlenecks in training large models.

This co-design is why our full-stack solutions perform so well.

### Enterprise Strategy

**Ben Thompson:** How do you approach the enterprise market differently from hyperscalers?

**Jensen Huang:** Enterprises want pragmatism. Start with proven use cases. Show ROI. Minimize risk.

Hyperscalers are pushing the frontier. They want the latest, most powerful hardware. They'll build custom infrastructure. They accept complexity.

Enterprises want solutions. They want pre-integrated systems. They want time-to-value measured in weeks, not years.

NVIDIA addresses both. DGX Cloud for hyperscalers. DGX systems for enterprises. NIM microservices for quick deployment. AI Foundry for customization.

**Ben Thompson:** Does selling components undermine your full-stack strategy?

**Jensen Huang:** Not at all. It's additive.

Some customers want the full NVIDIA stack — hardware, software, networking, AI models. Some want just GPUs. Some want GPUs plus CUDA. Some want inference services.

We meet customers where they are. The key is that everything works together when they want it to, and independently when they don't.

### Gaming's Strategic Importance

**Ben Thompson:** Gaming still matters strategically?

**Jensen Huang:** Absolutely. Three reasons:

First, gaming funds our R&D. The gaming market is large and profitable. It pays for the fundamental graphics research that benefits everything else.

Second, gaming is the testbed. Ray tracing, DLSS, AI graphics — gaming validates these before they go to pro visualization, simulation, etc.

Third, gamers are the power users. They push technology to limits. Their feedback improves our products.

Gaming is not separate from our AI strategy. It's foundational to it.

### NVIDIA's Evolution

**Ben Thompson:** How has NVIDIA changed as a company?

**Jensen Huang:** We've reinvented ourselves three times.

First: we were a graphics company. Gaming, professional visualization.

Second: we became a computing company. CUDA made GPUs programmable. Scientific computing, AI research.

Third: we're now a data center scale company. AI factories, inference infrastructure, enterprise solutions.

Same DNA — accelerated computing. But the scale and scope have grown exponentially.

We're still reinventing ourselves. That's the job.

### The Future of AI Infrastructure

**Ben Thompson:** Where does this go?

**Jensen Huang:** Three trends:

First: inference scales massively. Every application will generate tokens. The compute required will be enormous.

Second: physical AI. Robotics, autonomous systems. AI that understands and moves in the physical world.

Third: ubiquitous AI. AI in every device, every application, everywhere.

Each trend requires infrastructure. That's what we build.

The specifics will surprise us. But the direction is clear: more compute, more AI, more intelligence embedded in everything.

---

## Key Themes

### 1. Dual-Track Strategy
- Hyperscalers: Frontier, scale, complex
- Enterprises: Pragmatic, ROI, integrated
- Both served by same technology, different packaging

### 2. Full-Stack Flexibility
- Full-stack maximizes performance when desired
- Components available independently
- Ecosystem integration maintained
- Customer choice preserved

### 3. Software-Hardware Co-Design
- Not just faster chips
- Optimized for actual workloads
- FP4, Transformer Engine from customer feedback
- Performance comes from integration

### 4. Inference Complexity
- Routing, load balancing, distributed execution
- Dynamo abstracts complexity
- Every GPU generation gets faster automatically
- Infrastructure matters as much as hardware

### 5. Gaming as Foundation
- Funds R&D
- Testbed for new technologies
- Power users provide feedback
- Graphics and AI share DNA

---

## Related Content

- See also: GTC 2024 Keynote
- See also: CSIS Fireside Chat
- See also: Milken Global Conference

---

## Tags

#persona #transcript #jensen-huang #stratechery #ben-thompson #dynamo #inference #full-stack #enterprise #hyperscalers #gaming
