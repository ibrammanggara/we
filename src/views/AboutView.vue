<script>
export default {
  data() {
    return {
      activeTab: 1,
      tech: [
        {
          id: 1,
          name: 'HTML',
          imageUrl: 'https://cdn-icons-png.flaticon.com/512/1051/1051277.png',
          status: 'Rank E 😮'
        },
        {
          id: 2,
          name: 'CSS',
          imageUrl: 'https://cdn-icons-png.flaticon.com/512/732/732190.png',
          status: 'Rank F 🥴'
        },
        {
          id: 3,
          name: 'Javascript',
          imageUrl: 'https://cdn.icon-icons.com/icons2/2415/PNG/512/javascript_original_logo_icon_146455.png',
          status: 'Rank F 🥴'
        },
        {
          id: 4,
          name: 'PHP',
          imageUrl: 'https://cdn.iconscout.com/icon/free/png-256/free-php-2038871-1720084.png',
          status: 'Rank F 🥴'
        },
      ],
      aws: [
      {
          id: 1,
          name: 'VPC',
          imageUrl: 'https://fileuplodsm.s3.amazonaws.com/file/vpc.png',
          status: 'Rank sss 😎'
        },
        {
          id: 2,
          name: 'Route 53',
          imageUrl: 'https://fileuplodsm.s3.amazonaws.com/file/r53.png',
          status: 'Rank sss 😎'
        },
        {
          id: 3,
          name: 'Cloudfront',
          imageUrl: 'https://fileuplodsm.s3.amazonaws.com/file/cloudfront.png',
          status: 'Rank sss 😎'
        },
        {
          id: 4,
          name: 'Elastic Beanstalk',
          imageUrl: 'https://fileuplodsm.s3.amazonaws.com/file/bns.png',
          status: 'Rank sss 😎'
        },
        {
          id: 5,
          name: 'Cloud 9',
          imageUrl: 'https://fileuplodsm.s3.amazonaws.com/file/c9.png',
          status: 'Rank sss 😎'
        },
        {
          id: 6,
          name: 'RDS',
          imageUrl: 'https://fileuplodsm.s3.amazonaws.com/file/rds.png',
          status: 'Rank sss 😎'
        },
        {
          id: 7,
          name: 'Dynamo DB',
          imageUrl: 'https://fileuplodsm.s3.amazonaws.com/file/dynamodb.png',
          status: 'Rank sss 😎'
        },
        {
          id: 8,
          name: 'EC2',
          imageUrl: 'https://fileuplodsm.s3.amazonaws.com/file/ec2.png',
          status: 'Rank sss 😎'
        },
        {
          id: 9,
          name: 'EBS',
          imageUrl: 'https://fileuplodsm.s3.amazonaws.com/file/ebs.png',
          status: 'Rank sss 😎'
        },
        {
          id: 10,
          name: 'EFS',
          imageUrl: 'https://fileuplodsm.s3.amazonaws.com/file/efs.png',
          status: 'Rank sss 😎'
        },
        {
          id: 11,
          name: 'S3 Bucket',
          imageUrl: 'https://fileuplodsm.s3.amazonaws.com/file/s3b.png',
          status: 'Rank sss 😎'
        },
        {
          id: 12,
          name: 'ECS',
          imageUrl: 'https://fileuplodsm.s3.amazonaws.com/file/ecs.png',
          status: 'Rank sss 😎'
        }
      ],
      tools: [
        {
          id: 1,
          name: 'GitHub',
          imageUrl: 'https://cdn-icons-png.flaticon.com/512/25/25231.png',
          status: 'Git Hosting'
        },
        {
          id: 2,
          name: 'Filezila',
          imageUrl: 'https://fileuplodsm.s3.amazonaws.com/file/fl.png',
          status: 'File Transfer Protocol'
        },
        {
          id: 3,
          name: 'Remmina',
          imageUrl: 'https://fileuplodsm.s3.amazonaws.com/file/rma.png',
          status: 'Remote Desk Protocol'
        },
        {
          id: 4,
          name: 'Cloudflare',
          imageUrl: 'https://fileuplodsm.s3.amazonaws.com/file/cf.png',
          status: 'Content Del Net'
        },
        {
          id: 5,
          name: 'Postgresql',
          imageUrl: 'https://fileuplodsm.s3.amazonaws.com/file/pgadmin.png',
          status: 'Database client'
        },
        {
          id: 6,
          name: 'Mysql',
          imageUrl: 'https://fileuplodsm.s3.amazonaws.com/file/mysql.png',
          status: 'Database client'
        }
      ]
    };
  }
}
</script>
<template>
  <div
    class="bg-[#1e1e1f] px-5 py-5 md:px-12 md:py-10 text-left border border-[#383838] rounded-3xl text-amber-50 mx-3 mb-5">
    <article data-page="about">

      <header>
        <div class="text-2xl font-bold text-white mb-5 fadein-bot title-section flex items-center">
          About Me &nbsp;
          <div class="h-[1px] w-32 bg-amber-200 md:w-96 aos-init aos-animate" data-aos="zoom-in-left"
            data-aos-duration="600"></div>
        </div>
      </header>

      <section
        class="text-sm md:text-lg text-justify flex flex-col gap-4 md:flex-row md:gap-8 md:justify-left md:items-center">
        <div class="flex justify-center">
          <img class="w-9/12 rounded-full mb-3 fadein-up"
            src="https://fileuplodsm.s3.amazonaws.com/file/Screenshot+from+2024-07-07+12-51-14.png" alt="Foto">
        </div>
        <div class="md:w-7/12">
          <p class="mb-3 md:mb-7 fadein-left fadeins-1">
            &nbsp; &nbsp; &nbsp; Hi everybody! My name is Ibram Manggara. I am a Cloud Engineer I have experience in managing servers. I really enjoy what I am doing at the moment, in my opinion servers are very important in all aspects of managing in the internet network.
          </p>
          <p class="mb-3 fadein-left fadeins-2">
            &nbsp; &nbsp; &nbsp; My job is to build an infrastructure for you that is functional and user cost friendly. Additionally, I add a personal touch to your infrastructure and ensure that it runs smoothly. My goal is to create a cost-friendly infrastructure for you. If you are interested in hiring me, please contact me.
          </p>
        </div>

      </section>

    </article>
  </div>

  <div class="px-5 py-5 md:px-12 md:py-10 text-left text-amber-50 mx-3">
    <article data-page="about">
      <header>
        <div class="text-2xl font-bold text-white mb-5 fadein-bot title-section flex items-center">
          <div class="h-[1px] w-10 bg-amber-200 md:w-20 aos-init aos-animate" data-aos="zoom-in-left"
            data-aos-duration="600"></div>
          &nbsp; Skills
        </div>
      </header>
      <section>
        <div>
          <ul class="flex flex-wrap text-sm font-medium text-center text-gray-500 dark:text-gray-400 mb-5">
            <li class="mr-2">
              <button class="inline-block px-4 py-3 rounded-lg hover:text-white"
                :class="{ 'text-amber-200 bg-amber-200 bg-opacity-10': activeTab === 1 }" @click="activeTab = 1">Language Stack</button>
            </li>
            <li class="mr-2">
              <button class="inline-block px-4 py-3 rounded-lg hover:text-white"
                :class="{ 'text-amber-200 bg-amber-200 bg-opacity-10': activeTab === 2 }" @click="activeTab = 2">AWS Cloud</button>
            </li>
            <li class="mr-2">
              <button class="inline-block px-4 py-3 rounded-lg hover:text-white"
                :class="{ 'text-amber-200 bg-amber-200 bg-opacity-10': activeTab === 3 }" @click="activeTab = 3">Tools</button>
            </li>
          </ul>
        </div>
        <div v-show="activeTab === 1">
          <div class="grid grid-cols-2 gap-4 pb-32 md:grid-cols-3 md:gap-8 xl:grid-cols-4 xl:gap-10 2xl:gap-12">
            <div v-for="item in tech" :key="item.id">
              <div
                class="item-tech flex cursor-pointer items-center gap-2 rounded border border-amber-200 px-2 py-2 hover:bg-amber-200 hover:bg-opacity-10 md:gap-3 lg:px-3 backdrop-blur-md bg-[#121212] bg-opacity-20">
                <div class="flex h-12 w-12 items-center justify-center p-0 lg:h-16 lg:w-16 lg:p-2 zoom-in">
                  <img alt="HTML" loading="lazy" width="32" height="32" decoding="async" data-nimg="1"
                    class="img-tech drop-shadow-xl transition-all duration-300 h-[65%] w-[65%] lg:h-[85%] lg:w-[85%]  "
                    :src="item.imageUrl" style="color: transparent;">
                </div>
                <div class="flex items-center text-sm md:text-base lg:text-lg">
                  <div class="tech font-medium text-secondary transition-all duration-300 translate-y-0 ">{{ item.name }}
                  </div>
                  <div
                    class="status-tech opacity-0 absolute mt-5 text-[10px] text-amber-200 transition-all duration-300 md:text-xs lg:text-sm">
                    {{ item.status }}</div>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div v-show="activeTab === 2">
          <div class="grid grid-cols-2 gap-4 pb-32 md:grid-cols-3 md:gap-8 xl:grid-cols-4 xl:gap-10 2xl:gap-12">
            <div v-for="item in aws" :key="item.id">
              <div
                class="item-tech flex cursor-pointer items-center gap-2 rounded border border-amber-200 px-2 py-2 hover:bg-amber-200 hover:bg-opacity-10 md:gap-3 lg:px-3 backdrop-blur-md bg-[#121212] bg-opacity-20">
                <div class="flex h-12 w-12 items-center justify-center p-0 lg:h-16 lg:w-16 lg:p-2 zoom-in">
                  <img alt="HTML" loading="lazy" width="32" height="32" decoding="async" data-nimg="1"
                    class="img-tech drop-shadow-xl transition-all duration-300 h-[65%] w-[65%] lg:h-[85%] lg:w-[85%]  "
                    :src="item.imageUrl" style="color: transparent;">
                </div>
                <div class="flex items-center text-sm md:text-base lg:text-lg">
                  <div class="tech font-medium text-secondary transition-all duration-300 translate-y-0 ">{{ item.name }}
                  </div>
                  <div
                    class="status-tech opacity-0 absolute mt-5 text-[10px] text-amber-200 transition-all duration-300 md:text-xs lg:text-sm">
                    {{ item.status }}</div>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div v-show="activeTab === 3">
          <div class="grid grid-cols-2 gap-4 pb-32 md:grid-cols-3 md:gap-8 xl:grid-cols-4 xl:gap-10 2xl:gap-12">
            <div v-for="item in tools" :key="item.id">
              <div
                class="item-tech flex cursor-pointer items-center gap-2 rounded border border-amber-200 px-2 py-2 hover:bg-amber-200 hover:bg-opacity-10 md:gap-3 lg:px-3 backdrop-blur-md bg-[#121212] bg-opacity-20">
                <div class="flex h-12 w-12 items-center justify-center p-0 lg:h-16 lg:w-16 lg:p-2 zoom-in">
                  <img alt="HTML" loading="lazy" width="32" height="32" decoding="async" data-nimg="1"
                    class="img-tech drop-shadow-xl transition-all duration-300 h-[65%] w-[65%] lg:h-[85%] lg:w-[85%]  "
                    :src="item.imageUrl" style="color: transparent;">
                </div>
                <div class="flex items-center text-sm md:text-base lg:text-lg">
                  <div class="tech font-medium text-secondary transition-all duration-300 translate-y-0 ">{{ item.name }}
                  </div>
                  <div
                    class="status-tech opacity-0 absolute mt-5 text-[10px] text-amber-200 transition-all duration-300 md:text-xs lg:text-sm">
                    {{ item.status }}</div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>
    </article>
  </div>
</template>

<style>
.fadein-left {
  opacity: 0;
  animation: fadeInLeft 0.5s ease-out forwards;
}

@keyframes fadeInLeft {
  0% {
    opacity: 0;
    transform: translateX(100%);
  }

  100% {
    opacity: 1;
    transform: translateX(0);
  }
}

.fadeins-1 {
  animation-delay: 500ms;
}

.fadeins-2 {
  animation-delay: 800ms;
}

.img-tech,
.tech {
  transition: transform 0.3s ease;
}

.item-tech:hover .img-tech {
  transform: scale(1.3);
}

.item-tech:hover .tech {
  transform: translateY(-12px);
}

.item-tech:hover .status-tech {
  opacity: 1;
}
</style>
