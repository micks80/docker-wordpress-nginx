node {
    
  stage 'Checkout'
  git 'https://github.com/micks80/docker-wordpress-nginx.git'
  
  stage 'Package Docker image'
  def img = docker.build('micks80/docker-wordpress-nginx:latest', '.')

  stage 'Publish'

}
