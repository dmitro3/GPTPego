# GPTStore - Powered by OpenAI Assistant

## Overview

GPTStore is an innovative initiative that leverages the capabilities of the OpenAI Assistant to establish a dynamic ecosystem for developers. This platform enables users to effortlessly build and train AI Dev Advocates, facilitating the seamless sharing of domain-specific knowledge. Developers can monetize their efforts by renting out their AI Dev Advocates, providing others with time-based access to these intelligent assistants.

## Inspiration

The inspiration behind the AI Dev Advocate Platform is our collective aspiration to empower developers with easy access to accurate and real-time information. Our vision is to create a platform where developers can engage in meaningful conversations with AI Dev Advocates, offering a unique and effective way to explore and comprehend complex concepts.

Traditional language models often struggle in rapidly evolving domains due to knowledge cutoffs. The AI Dev Advocate Platform aims to overcome these limitations by harnessing the OpenAI Assistant's ability to adapt to the dynamic nature of today's information landscape.

## Functionality

The AI Dev Advocate Platform streamlines the process of creating AI Dev Advocates. Users can input a knowledge URL, specify the number of pages for crawling and indexing, and customize details such as name, description, pricing, and logo. The generated AI Dev Advocates are then made available on the platform for others to rent. Renters gain access based on their rented time, and automated systems ensure access revocation when the rental period concludes.

## Monetization Strategy

To sustain the AI Dev Advocate Platform and support the usage of the OpenAI Assistant, we have implemented a unique monetization strategy. Users generate revenue (AVX) by renting out their AI Dev Advocates. The funds generated through rentals are allocated to cover the costs of OpenAI keys, ensuring continuous access to the powerful OpenAI Assistant.

### Why Rental Method?

The decision to adopt a rental method over traditional monthly subscriptions is driven by several factors:

1. **Fair Usage**: The rental method ensures fair compensation for users based on the actual utilization of AI Dev Advocates. Users pay for the time they actively use the service, promoting fairness in pricing.

2. **Cost-Efficiency**: Renting allows users with occasional or project-specific needs to access AI Dev Advocates without committing to a fixed monthly subscription. This flexibility caters to diverse user requirements, making the platform more accessible.

3. **Resource Optimization**: By adopting a rental model, users can optimize resource allocation and costs based on their specific needs. This approach aligns with our commitment to providing a cost-effective and efficient solution for users.

## Technology Stack

- Next.js
- Express
- Solidity
- OpenAI Assistant

## Accomplishments

The GPTStore has successfully implemented core functionalities, including AI Dev Advocate creation, renting, Chainlink automation, price feed integration for dynamic pricing, and CCIP for cross-chain operations.

## Learning Experience

The integration of Chainlink CCIP has provided valuable insights into seamless cross-chain communication, enriching the team with a deeper understanding of blockchain interoperability.

## Future Roadmap

As the AI Dev Advocate Platform evolves, our vision extends beyond the current capabilities. We plan to diversify by incorporating additional web3 protocols, creating a vibrant ecosystem where users can craft specialized AI Dev Advocates tailored to distinct knowledge domains. The roadmap envisions a dynamic platform, fostering a community-driven marketplace for knowledge-sharing through rented AI Dev Advocates.

## Try It Out

- [GitHub](https://github.com/nwakaku/GPTStore)
- [Website](https://gptstore.gitbook.io/gptstore-documentation-horizon/)
- [YouTube](https://www.youtube.com/watch?v=HJOp9F2Xlak)

### Running Locally
1. Clone the project
2. Navigate to the `backend` directory
3. Rename `.env.example` to `.env` and provide your `OPENAI_API` key
4. Run `npm install`
5. Run `npm run start`
6. Navigate to the root directory and then to the `frontend` directory
7. Rename `.env.example` to `.env` and provide your `NFT_STORAGE_TOKEN`
8. Run `npm install`
9. Run `npm run dev`
10. Open [http://localhost:3000](http://localhost:3000) in your browser