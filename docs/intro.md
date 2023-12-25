---
sidebar_position: 1
---

# 📖 Description

This application is built using a microservices architecture with [Nest](https://nestjs.com/) and [RabbitMQ](https://www.rabbitmq.com/). It includes the following features:

- **Infrastructure:**

  - Monorepo with [Nest Monorepo](https://docs.nestjs.com/cli/monorepo#monorepo-mode)
  - Containerization with [Docker](https://www.docker.com/) and [Docker Compose](https://docs.docker.com/compose/)
  - Message Broker with [RabbitMQ](https://www.rabbitmq.com/)
  - Cache with [Redis](https://redis.io/)
  - Database with [MongoDB](https://www.mongodb.com/)
  - Job queue with [BullMQ](https://bullmq.io/)
  - Deploy with [Google Cloud](https://cloud.google.com/), [Azure](https://azure.microsoft.com/), and other cloud services
  - Continuous Integration with [Github Actions](https://github.com/features/actions)
  - Reverse proxy with [Nginx](https://www.nginx.com/)
  - SSL with [Let's Encrypt](https://letsencrypt.org/), [ZeroSSL](https://zerossl.com/), and [Cloudflare](https://www.cloudflare.com/)
  - High availability with [HAProxy](https://www.haproxy.org/)

- **Features:**
  - User, Profile, Product, Order, Category, Notification, Attribute, Cart, Otp management ...
  - Transaction order with [Mongodb transaction](https://docs.mongodb.com/manual/core/transactions/) and distributed lock with [Redlock](https://redis.io/topics/distlock)
  - Multi languages with [i18n](https://www.npmjs.com/package/i18n)
  - Authentication with [JWT](https://jwt.io/)
  - Login, sign up with Credentials (email verified), Google
  - Storage with [Cloudinary](https://cloudinary.com/)
  - Custom domain emails with [Sendgrid](https://sendgrid.com/), [Resend](https://resend.com/), and [Gmail](https://mail.google.com/)
  - Notifications with [Socket.io](https://socket.io/), using job queue to send notifications
  - Cron jobs to clean unused data
  - Payment integration with [VNPay](https://vnpay.vn/)
  - Shipping integration with [GiaoHangNhanh](https://ghn.vn/)
