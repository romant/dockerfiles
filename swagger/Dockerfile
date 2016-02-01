#
# used for Grant Orchard's FAPI Project
# for the make benefit of vRA API Swagger Documentation
# 
# as seen on http://github.com/vmware/fapi
#
# must be used in conjuction with the Swagger UI

FROM romant/node:4.2.4

MAINTAINER Roman Tarnavski - @romant

WORKDIR /app

COPY ./ui /app

RUN npm install

EXPOSE 8080

CMD /app/node_modules/gulp/bin/gulp.js serve