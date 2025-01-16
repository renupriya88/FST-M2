# Set base image , most common used alpine(smallest linux operating sytem, smallest 4MB)	
# Use an existing image as a base
FROM docker.io/alpine
	
# Create a Work Directory(all coding is done here, common path is /usr/app)
# mkdir and cd command is done here, usr is present inbuilt in Linux, user folder, every user accessible)
WORKDIR /usr/app
	
# Download and install a dependency
RUN apk add --update redis
	
# Tell the image what to do when it starts
# as a container
CMD ["redis-server"]