# cloud-server


## Links
- http://lab16-cli-eb.eba-zi6iz5dz.us-east-1.elasticbeanstalk.com/
- http://lab16-gui-env.eba-xe3agbzz.us-east-1.elasticbeanstalk.com/



## Notes
### Elastic Beanstalk GUI 
1. Navigate to the Elastic Beanstalk AWS GUI [link](https://us-east-1.console.aws.amazon.com/elasticbeanstalk/home?region=us-east-1)
2. Select **Create Environment**
3. You can leave most of the options as they are, except for the required ones:
   1. Application name
   2. Environment name
   3. Upload your code (must be a .zip)

### eb cli

1. `eb init`
2. choose the default options
3. `eb create --single <my-environment-name>` to create your new environment
4. `eb deploy` 