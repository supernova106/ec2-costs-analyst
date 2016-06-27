##Info
- To analyze the EC2 instance costs for one region
- Support Spot Instance, Ondemand Instance and RI 
- List which RI is not in used
- Potential savings if replace OD with Spot or RI (if available)
##setup  
```
python setup.py install
```
```
export AWS_ACCESS_KEY_ID=''
export AWS_SECRET_ACCESS_KEY='' 
```
--format: is optional (blank for stdout)
```
python analyze.py --region=us-east-1 --format=xlsx
```
##contact
- Binh Nguyen
